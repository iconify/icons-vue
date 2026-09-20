<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/g_8lrzb7q.css';
import '../../css/x/x-exdccqr.css';
import '../../css/s/so9dkqjrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="g_8lrzb7q"/><path class="x-exdccqr"/><path class="so9dkqjrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrow-up-right" /></template>
