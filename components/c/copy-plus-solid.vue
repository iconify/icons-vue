<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwobixbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwobixbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-plus-solid" /></template>
