<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aamwa-sar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aamwa-sar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:antenna-bars-5" /></template>
