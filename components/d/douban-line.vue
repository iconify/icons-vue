<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9pr4_bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9pr4_bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:douban-line" /></template>
