<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbe_snv5s.css';
import '../../css/h/hxb2u__jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qbe_snv5s"/><path class="hxb2u__jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:chef-toque-hat-solid" /></template>
