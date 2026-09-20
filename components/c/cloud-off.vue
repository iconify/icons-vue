<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upvyt2bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upvyt2bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-off" /></template>
