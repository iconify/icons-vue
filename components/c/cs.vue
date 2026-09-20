<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ljnzsybuh.css';
import '../../css/p/pfb-g5f5t.css';
import '../../css/p/pop0a3r2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="ljnzsybuh"/><path class="pfb-g5f5t"/><path class="pop0a3r2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:cs" /></template>
