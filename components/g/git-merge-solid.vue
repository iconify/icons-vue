<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luof2w8us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luof2w8us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:git-merge-solid" /></template>
