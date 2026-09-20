<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lndg6lbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lndg6lbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-side" /></template>
