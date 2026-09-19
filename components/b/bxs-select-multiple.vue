<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_99-bnr.css';
import '../../css/l/l_u7c-bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_99-bnr"/><path class="l_u7c-bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-select-multiple" /></template>
