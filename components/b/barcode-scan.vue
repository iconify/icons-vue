<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y83a6fpaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y83a6fpaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:barcode-scan" /></template>
