<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w01qq6qdq.css';
import '../../css/m/m_r-rybts.css';
import '../../css/u/uvd1g15ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="rotate(-90 10 8)" class="bi12bsetm"><path class="w01qq6qdq"/><circle class="m_r-rybts"/><path class="uvd1g15ov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:harddrive" /></template>
