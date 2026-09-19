<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d14nygiuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d14nygiuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dyson-desk" /></template>
