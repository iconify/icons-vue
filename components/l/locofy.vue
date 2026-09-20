<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/b/b16z9cbwi.css';
import '../../css/e/eihi2zo4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48.3,"height":48.3};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><circle class="b16z9cbwi"/><path class="eihi2zo4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:locofy" /></template>
