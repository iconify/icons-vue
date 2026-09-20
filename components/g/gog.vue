<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/febz36opq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="febz36opq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gog" /></template>
