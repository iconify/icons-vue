<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps1rxzboz.css';
import '../../css/n/nug-zhhlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1rxzboz"/><path class="nug-zhhlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-qr-scan" /></template>
