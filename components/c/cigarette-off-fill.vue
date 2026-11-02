<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw9ndx6fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw9ndx6fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cigarette-off-fill" /></template>
