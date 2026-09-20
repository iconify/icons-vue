<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8vlxmbmn.css';
import '../../css/g/g-4pifb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="l8vlxmbmn"/><path clip-rule="evenodd" class="g-4pifb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bitcoin" /></template>
