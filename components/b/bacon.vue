<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8i2_7vnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8i2_7vnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bacon" /></template>
