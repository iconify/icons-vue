<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxgsqdbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxgsqdbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-gbp" /></template>
