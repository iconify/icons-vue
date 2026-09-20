<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz3ldbc-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz3ldbc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hbo" /></template>
