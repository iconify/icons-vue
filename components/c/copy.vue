<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2_fu_bwp.css';
import '../../css/r/r42-uz-ln.css';
import '../../css/f/fnyksabiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2_fu_bwp"/><path class="r42-uz-ln"/><path class="fnyksabiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:copy" /></template>
