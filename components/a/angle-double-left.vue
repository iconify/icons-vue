<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm2utoh2v.css';
import '../../css/b/bubzgdclu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="bm2utoh2v"/><path class="bubzgdclu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:angle-double-left" /></template>
