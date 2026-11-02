<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsldembvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsldembvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fishing-rod-fill" /></template>
