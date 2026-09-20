<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss-z11x0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss-z11x0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:frame" /></template>
