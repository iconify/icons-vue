<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uridksyau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uridksyau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:instapaper" /></template>
