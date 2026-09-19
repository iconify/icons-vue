<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8ccp12wz.css';
import '../../css/n/nzx_vzkit.css';
import '../../css/e/e-u7_pwmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h8ccp12wz"/><path class="nzx_vzkit"/><path class="e-u7_pwmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:axe" /></template>
