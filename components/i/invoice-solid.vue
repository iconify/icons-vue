<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ariwul1cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ariwul1cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:invoice-solid" /></template>
