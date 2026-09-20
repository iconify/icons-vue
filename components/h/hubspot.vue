<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gof9z4p8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gof9z4p8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hubspot" /></template>
