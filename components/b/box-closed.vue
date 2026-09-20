<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc-uk6b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="wc-uk6b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:box-closed" /></template>
