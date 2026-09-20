<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3dqu4bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3dqu4bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:luanti" /></template>
