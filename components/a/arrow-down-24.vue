<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdrja8e0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrja8e0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-down-24" /></template>
