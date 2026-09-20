<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndu43bc7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndu43bc7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:color-picker-off" /></template>
