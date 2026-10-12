<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7c8n5bpv.css';
import '../../css/o/obndhi7my.css';
import '../../css/i/itu66bbfs.css';
import '../../css/f/f2mixfbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y7c8n5bpv"/><path class="obndhi7my"/><path class="itu66bbfs"/><path class="f2mixfbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gem-20" /></template>
