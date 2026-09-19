<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgmhddevn.css';
import '../../css/a/avi7ktl-p.css';
import '../../css/e/e_wydyb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="avi7ktl-p"/><path class="e_wydyb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asset-view" /></template>
