<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdgey5bpj.css';
import '../../css/z/zxi_dh3ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdgey5bpj"/><path class="zxi_dh3ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-barcode" /></template>
