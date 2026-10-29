<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7a_y8vaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7a_y8vaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:barcode" /></template>
