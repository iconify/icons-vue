<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cas24ccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cas24ccaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-l-hexagon-solid" /></template>
