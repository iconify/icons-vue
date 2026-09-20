<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc-3dgb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="qc-3dgb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chevron-left" /></template>
