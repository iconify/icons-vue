<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6thu1bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6thu1bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:blockchaindotcom" /></template>
