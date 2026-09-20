<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfg8lvbrj.css';
import '../../css/w/whb5utbty.css';
import '../../css/f/frxdtjj9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfg8lvbrj"/><path class="whb5utbty"/><path class="frxdtjj9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-docs-dark" /></template>
