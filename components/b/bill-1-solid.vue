<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uljoi_ege.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uljoi_ege"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bill-1-solid" /></template>
