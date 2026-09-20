<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhj0e-blr.css';
import '../../css/e/etqe0ibeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zhj0e-blr"/><path clip-rule="evenodd" class="etqe0ibeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cup-solid" /></template>
