<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdct5dbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdct5dbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-circle" /></template>
