<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjpslx8tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjpslx8tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-pair-gloss" /></template>
