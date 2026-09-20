<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sn01zlbqh.css';
import '../../css/m/mc4n-6bac.css';
import '../../css/z/zm6gsmbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="sn01zlbqh"/><path class="mc4n-6bac"/><path class="zm6gsmbpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrow-left" /></template>
