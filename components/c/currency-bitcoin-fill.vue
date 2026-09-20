<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixwejgkiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixwejgkiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-bitcoin-fill" /></template>
