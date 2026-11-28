<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mwci43k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1mwci43k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:caret-up" /></template>
