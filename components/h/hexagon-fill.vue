<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-0r88qhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-0r88qhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hexagon-fill" /></template>
