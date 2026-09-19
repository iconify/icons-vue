<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzndw_apr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzndw_apr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:etsy" /></template>
