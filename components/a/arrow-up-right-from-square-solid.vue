<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h8c9mcc0r.css';
import '../../css/t/tqd_5obmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h8c9mcc0r"/><path class="tqd_5obmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-up-right-from-square-solid" /></template>
