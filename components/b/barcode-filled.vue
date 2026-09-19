<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrmz5hbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrmz5hbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:barcode-filled" /></template>
