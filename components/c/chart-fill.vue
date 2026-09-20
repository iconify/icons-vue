<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gll1qohkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gll1qohkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chart-fill" /></template>
