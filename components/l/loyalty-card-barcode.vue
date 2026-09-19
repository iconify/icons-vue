<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohifcbcwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohifcbcwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:loyalty-card-barcode" /></template>
