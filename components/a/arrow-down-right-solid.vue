<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7my3gbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7my3gbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-down-right-solid" /></template>
