<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g5fj2gb9b.css';
import '../../css/s/s1kzwjbvm.css';
import '../../css/d/dh_uqzb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g5fj2gb9b"/><path class="s1kzwjbvm"/><path clip-rule="evenodd" class="dh_uqzb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bills" /></template>
