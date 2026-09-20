<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmi0gnlre.css';
import '../../css/g/gcnxx2xsc.css';
import '../../css/z/zopjch_2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xmi0gnlre"><path class="gcnxx2xsc"/><circle class="zopjch_2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:alarm-fill" /></template>
