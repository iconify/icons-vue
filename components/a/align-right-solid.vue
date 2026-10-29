<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhad7acyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhad7acyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-right-solid" /></template>
