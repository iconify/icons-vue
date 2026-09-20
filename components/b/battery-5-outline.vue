<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7646jdal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j7646jdal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-5-outline" /></template>
