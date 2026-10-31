<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udd7sr0oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udd7sr0oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-fill-round" /></template>
