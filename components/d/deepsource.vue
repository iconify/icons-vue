<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7veribva.css';
import '../../css/b/bpjvsabdv.css';
import '../../css/k/koxyqebxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7veribva"/><path class="bpjvsabdv"/><path class="koxyqebxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:deepsource" /></template>
