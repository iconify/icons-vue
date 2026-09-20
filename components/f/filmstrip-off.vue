<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fel89onfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fel89onfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filmstrip-off" /></template>
