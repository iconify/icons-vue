<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc5a79bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xc5a79bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bag-solid" /></template>
