<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erc0k0b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erc0k0b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:earth" /></template>
