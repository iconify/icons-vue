<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iee106p3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iee106p3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dice-3" /></template>
