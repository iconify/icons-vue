<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn1h0gzdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn1h0gzdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fire-engine" /></template>
