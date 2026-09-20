<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po44rxx7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="po44rxx7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-double-20-solid" /></template>
