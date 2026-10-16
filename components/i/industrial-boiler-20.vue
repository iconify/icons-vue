<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwuwdzb4d.css';
import '../../css/b/bxnfngy9v.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kwuwdzb4d"/><path class="bxnfngy9v"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:industrial-boiler-20" /></template>
