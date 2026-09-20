<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydh0_hbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydh0_hbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grill" /></template>
