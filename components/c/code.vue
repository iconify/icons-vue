<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/ohtbcybba.css';
import '../../css/i/iqj-84gkn.css';
import '../../css/s/sp0fyfs-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ohtbcybba"/><path class="iqj-84gkn"/><path class="sp0fyfs-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:code" /></template>
