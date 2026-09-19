<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv_l09bks.css';
import '../../css/k/kv-q3cc2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv_l09bks"/><path class="kv-q3cc2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:low-vision" /></template>
