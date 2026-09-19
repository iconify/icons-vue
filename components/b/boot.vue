<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2c_gdcrq.css';
import '../../css/h/hcr-277-p.css';
import '../../css/q/qen33gjlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="w2c_gdcrq"/><path class="hcr-277-p"/><path class="qen33gjlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:boot" /></template>
