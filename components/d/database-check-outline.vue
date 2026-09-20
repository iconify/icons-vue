<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4w_dm9xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4w_dm9xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-check-outline" /></template>
