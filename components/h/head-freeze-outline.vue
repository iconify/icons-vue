<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r22jfto4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r22jfto4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-freeze-outline" /></template>
