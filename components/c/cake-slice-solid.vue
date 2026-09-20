<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql1cgccil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ql1cgccil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cake-slice-solid" /></template>
