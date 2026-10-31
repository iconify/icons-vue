<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sasdp3y_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sasdp3y_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-check-gloss" /></template>
