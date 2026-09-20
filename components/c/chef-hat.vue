<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_w07d5xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k_w07d5xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chef-hat" /></template>
