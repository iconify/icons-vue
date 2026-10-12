<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g99mf4bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g99mf4bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cos" /></template>
