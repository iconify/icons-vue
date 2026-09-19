<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieveh1t1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieveh1t1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:domains" /></template>
