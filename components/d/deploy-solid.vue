<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6b1i7-3i.css';
import '../../css/p/p5gujlbxv.css';
import '../../css/m/m40-lvl0e.css';
import '../../css/v/vbxp9zbuq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 k6b1i7-3i"/><path class="clr-i-solid clr-i-solid-path-2 p5gujlbxv"/><path class="clr-i-solid clr-i-solid-path-3 m40-lvl0e"/><path class="clr-i-solid clr-i-solid-path-4 vbxp9zbuq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:deploy-solid" /></template>
