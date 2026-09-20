<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gafy37gmj.css';
import '../../css/s/sjlz8xm0b.css';
import '../../css/r/ri_ieprmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gafy37gmj"/><path clip-rule="evenodd" class="sjlz8xm0b"/><path clip-rule="evenodd" class="ri_ieprmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-transfer-bold" /></template>
