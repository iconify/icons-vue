<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr-fs73ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr-fs73ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-up" /></template>
