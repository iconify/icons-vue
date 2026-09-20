<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_ch9b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_ch9b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-right-2-line" /></template>
