<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os3wfcb2g.css';
import '../../css/d/duhv4jbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="os3wfcb2g"/><path class="duhv4jbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cat-20" /></template>
