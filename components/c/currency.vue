<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfcz5l1zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfcz5l1zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency" /></template>
