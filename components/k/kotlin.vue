<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su70yibof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su70yibof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:kotlin" /></template>
