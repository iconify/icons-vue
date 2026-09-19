<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo0137bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo0137bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fish-alt-filled" /></template>
