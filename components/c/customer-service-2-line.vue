<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1eobnak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz1eobnak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:customer-service-2-line" /></template>
