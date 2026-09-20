<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrhofjbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xrhofjbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bar-code" /></template>
