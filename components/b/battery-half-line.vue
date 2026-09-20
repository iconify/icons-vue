<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q280ddcrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q280ddcrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:battery-half-line" /></template>
