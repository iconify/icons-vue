<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpei1abib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpei1abib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-footer" /></template>
