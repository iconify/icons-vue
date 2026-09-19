<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af2n3wb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="af2n3wb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:finger-print-16-solid" /></template>
