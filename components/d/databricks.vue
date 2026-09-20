<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0lf3zb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0lf3zb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:databricks" /></template>
