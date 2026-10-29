<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/e/e3hfdmyvm.css';
import '../../css/e/e53dr11tv.css';
import '../../css/b/bqrd_rbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="e3hfdmyvm"/><path class="e53dr11tv"/><path class="bqrd_rbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bitcoin" /></template>
