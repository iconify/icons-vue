<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa48ywbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa48ywbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-right-from-line" /></template>
