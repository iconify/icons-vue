<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsszjbc5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="xsszjbc5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:direction-sign" /></template>
