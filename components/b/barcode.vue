<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zldz03bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zldz03bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:barcode" /></template>
