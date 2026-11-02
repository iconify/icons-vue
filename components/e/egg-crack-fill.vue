<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn6bvd5qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn6bvd5qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-crack-fill" /></template>
