<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh6l72_ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh6l72_ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-cny" /></template>
