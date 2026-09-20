<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zttm-7ynq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zttm-7ynq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-4" /></template>
