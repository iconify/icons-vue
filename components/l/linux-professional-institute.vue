<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr9w-81wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr9w-81wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:linux-professional-institute" /></template>
