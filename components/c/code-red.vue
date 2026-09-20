<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogl56j_pb.css';
import '../../css/d/ddop6km7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogl56j_pb"/><path class="ddop6km7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:code-red" /></template>
