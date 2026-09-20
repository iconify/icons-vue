<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/a8rhsbbes.css';
import '../../css/o/oaf9t3bzr.css';
import '../../css/s/ssnkahrib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="a8rhsbbes"/><path class="oaf9t3bzr"/><path class="ssnkahrib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrow-up-left" /></template>
