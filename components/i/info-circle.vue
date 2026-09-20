<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr9wr-bhx.css';
import '../../css/b/bd8f5nbwf.css';
import '../../css/m/mabwzbbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xr9wr-bhx"/><circle class="bd8f5nbwf"/><path class="mabwzbbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:info-circle" /></template>
