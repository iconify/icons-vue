<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t9xfl1oin.css';
import '../../css/y/ytlnqnvjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path clip-rule="evenodd" class="t9xfl1oin"/><path vector-effect="non-scaling-stroke" class="ytlnqnvjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:cancel-circle-filled" /></template>
