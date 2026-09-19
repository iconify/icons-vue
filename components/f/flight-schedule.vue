<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjzjafblt.css';
import '../../css/j/ji95cg_id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pjzjafblt"/><path class="ji95cg_id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flight-schedule" /></template>
