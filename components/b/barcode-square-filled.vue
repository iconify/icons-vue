<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoadq4yvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoadq4yvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:barcode-square-filled" /></template>
