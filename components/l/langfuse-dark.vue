<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0qakpzvw.css';
import '../../css/m/mhn4ay1xq.css';
import '../../css/t/ty23m0b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r0qakpzvw"/><path class="mhn4ay1xq"/><path class="ty23m0b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:langfuse-dark" /></template>
