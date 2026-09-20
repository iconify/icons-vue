<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dn9_0uvcp.css';
import '../../css/q/q8y8mzbgx.css';
import '../../css/o/oq8v77b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dn9_0uvcp"/><path class="q8y8mzbgx"/><path class="oq8v77b3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-add" /></template>
