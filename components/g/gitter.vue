<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-0xmhb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u-0xmhb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gitter" /></template>
