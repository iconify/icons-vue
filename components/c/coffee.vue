<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8c5h_bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8c5h_bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:coffee" /></template>
