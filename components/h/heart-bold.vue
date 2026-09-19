<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hss024hkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hss024hkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:heart-bold" /></template>
