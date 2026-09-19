<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dimhxxbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dimhxxbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:doublespot" /></template>
