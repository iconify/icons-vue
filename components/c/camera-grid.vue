<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v62pdisir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v62pdisir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:camera-grid" /></template>
