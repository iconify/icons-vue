<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/t1mywg2eu.css';
import '../../css/s/su_0fqb0p.css';
import '../../css/n/njxkiiehp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="t1mywg2eu"/><path class="su_0fqb0p"/><path class="njxkiiehp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-left" /></template>
