<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpe_dfizg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpe_dfizg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-euro-solid" /></template>
