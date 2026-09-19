<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv-jkn1sc.css';
import '../../css/z/zz0-pccgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nv-jkn1sc"/><path class="zz0-pccgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bug" /></template>
