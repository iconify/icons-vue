<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1hic9yix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k1hic9yix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:handshake" /></template>
