<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stepmxb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stepmxb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bread-off" /></template>
