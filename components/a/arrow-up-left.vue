<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gsx9jlw0a.css';
import '../../css/n/n_375sy8q.css';
import '../../css/i/i-ez_k42u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gsx9jlw0a"/><path class="n_375sy8q"/><path class="i-ez_k42u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-up-left" /></template>
