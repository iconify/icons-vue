<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e61bgw5xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e61bgw5xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:hash-fill" /></template>
