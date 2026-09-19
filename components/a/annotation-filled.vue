<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvwao29ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvwao29ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:annotation-filled" /></template>
