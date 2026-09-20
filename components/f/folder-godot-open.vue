<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa0d9wb7d.css';
import '../../css/r/rz1q6nuvq.css';
import '../../css/x/xrnpo0biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qa0d9wb7d"/><path class="rz1q6nuvq"/><path class="xrnpo0biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-godot-open" /></template>
