<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwa603yuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwa603yuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cone" /></template>
