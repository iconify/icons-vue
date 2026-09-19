<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imh9d0bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imh9d0bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-yen" /></template>
