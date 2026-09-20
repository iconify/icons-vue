<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbvihdspj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="mbvihdspj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-both" /></template>
