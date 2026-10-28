<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2nmbnbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2nmbnbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-right" /></template>
