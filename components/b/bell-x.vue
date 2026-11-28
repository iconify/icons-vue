<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7jp2kbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7jp2kbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bell-x" /></template>
