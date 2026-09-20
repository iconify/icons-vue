<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zkbga2bms.css';
import '../../css/i/i2qezbnqp.css';
import '../../css/q/q8wbu63xu.css';
import '../../css/d/dvxkj65od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><g class="zkbga2bms"><circle class="i2qezbnqp"/><path class="q8wbu63xu"/></g><circle class="dvxkj65od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:info-circle" /></template>
