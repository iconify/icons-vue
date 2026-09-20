<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0_5tr2wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b0_5tr2wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cloud-solid" /></template>
