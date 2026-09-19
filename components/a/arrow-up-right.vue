<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/plm7q3bkj.css';
import '../../css/k/ky0155huo.css';
import '../../css/h/h7cc31xbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="plm7q3bkj"/><path class="ky0155huo"/><path class="h7cc31xbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-up-right" /></template>
