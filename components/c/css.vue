<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t78rjtomt.css';
import '../../css/h/hn34necwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t78rjtomt"/><path class="hn34necwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:css" /></template>
