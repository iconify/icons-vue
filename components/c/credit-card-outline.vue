<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-zw0hbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-zw0hbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-outline" /></template>
