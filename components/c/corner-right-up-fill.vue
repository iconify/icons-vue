<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbayqnbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbayqnbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-right-up-fill" /></template>
