<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hnpa17iln.css';
import '../../css/p/p2z3ecb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="login-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="hnpa17iln"/><path class="p2z3ecb-h"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:login-outline" /></template>
