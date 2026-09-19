<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/uz5a9fb8c.css';
import '../../css/s/sqfsm7btn.css';
import '../../css/b/b98kc6bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="uz5a9fb8c"/><path class="sqfsm7btn"/><path class="b98kc6bwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:apple-one" /></template>
