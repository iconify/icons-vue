<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt_8w5b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt_8w5b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cyber" /></template>
