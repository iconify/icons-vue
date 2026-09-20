<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk3k_6m-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk3k_6m-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:barcode-off" /></template>
