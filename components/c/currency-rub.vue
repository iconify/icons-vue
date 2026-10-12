<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpav7h32m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpav7h32m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-rub" /></template>
