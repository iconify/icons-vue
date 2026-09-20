<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqvv5zbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqvv5zbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dots-vertical-fill" /></template>
