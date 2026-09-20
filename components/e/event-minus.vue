<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxq2d1-sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxq2d1-sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-minus" /></template>
