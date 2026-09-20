<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl2nwrbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl2nwrbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing-3" /></template>
