<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq4--5bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq4--5bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-box-fill" /></template>
