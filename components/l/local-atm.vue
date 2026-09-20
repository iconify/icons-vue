<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/totc_uaeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="totc_uaeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:local-atm" /></template>
