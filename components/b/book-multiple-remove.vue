<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrij_qbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrij_qbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-multiple-remove" /></template>
