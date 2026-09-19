<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fagdp1b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fagdp1b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-0306m-outline-24px" /></template>
