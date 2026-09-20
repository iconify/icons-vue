<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk8bvthsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="gk8bvthsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:claude" /></template>
