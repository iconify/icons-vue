<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsao1jbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsao1jbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-krw" /></template>
