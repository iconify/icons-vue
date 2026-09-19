<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbsqho_bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qbsqho_bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-bangladeshi-16-solid" /></template>
