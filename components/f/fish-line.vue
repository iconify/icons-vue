<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ards4o__f.css';
import '../../css/t/t0jstuirm.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="ards4o__f clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 t0jstuirm"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:fish-line" /></template>
