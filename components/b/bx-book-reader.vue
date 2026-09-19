<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oor5lmtnx.css';
import '../../css/v/v_ha0xbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oor5lmtnx"/><circle class="v_ha0xbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-book-reader" /></template>
