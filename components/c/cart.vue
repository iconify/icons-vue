<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk2g91wbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sk2g91wbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cart" /></template>
