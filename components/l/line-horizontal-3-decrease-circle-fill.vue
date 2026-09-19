<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhjon3l2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vhjon3l2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:line-horizontal-3-decrease-circle-fill" /></template>
