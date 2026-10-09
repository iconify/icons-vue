<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viu8vyokx.css';
import '../../css/j/jyz_jvb2h.css';
import '../../css/u/ugl4outhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="viu8vyokx"/><path class="jyz_jvb2h"/><path class="ugl4outhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leaf-alert-48" /></template>
