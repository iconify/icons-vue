<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvjsmgb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvjsmgb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-circle-diagonal-left" /></template>
