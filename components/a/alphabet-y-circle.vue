<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfp-bebsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfp-bebsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-y-circle" /></template>
