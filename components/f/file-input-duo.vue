<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bh88hfbbl.css';
import '../../css/l/l4vlz4b-i.css';
import '../../css/j/jnbx89z3f.css';
import '../../css/p/pnwuy2ujo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bh88hfbbl"/><path class="l4vlz4b-i wm-a"/><path class="jnbx89z3f"/><path class="pnwuy2ujo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-input-duo" /></template>
