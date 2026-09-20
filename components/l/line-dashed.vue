<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaw9wkb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="zaw9wkb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:line-dashed" /></template>
