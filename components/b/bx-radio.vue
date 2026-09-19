<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr7ox659t.css';
import '../../css/k/kqxojurgk.css';
import '../../css/d/d5l_p05mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr7ox659t"/><circle class="kqxojurgk"/><path class="d5l_p05mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-radio" /></template>
