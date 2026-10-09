<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wavel16di.css';
import '../../css/c/c07p4-7-o.css';
import '../../css/k/kzltt2bms.css';
import '../../css/d/d6cvwtbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wavel16di"/><path class="c07p4-7-o"/><path class="kzltt2bms"/><path class="d6cvwtbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forest-48-bold" /></template>
