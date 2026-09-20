<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfja7nbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nfja7nbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bread-slice-solid" /></template>
