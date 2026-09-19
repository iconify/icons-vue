<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upsvanbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upsvanbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-tubes-outline-24px" /></template>
