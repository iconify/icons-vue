<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvdq-vb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nvdq-vb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-after-effects" /></template>
