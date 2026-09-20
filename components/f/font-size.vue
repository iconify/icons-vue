<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/podsg1jia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="podsg1jia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:font-size" /></template>
