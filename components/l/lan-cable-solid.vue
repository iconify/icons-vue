<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztw2c0b2i.css';
import '../../css/u/u_7ar5bnj.css';
import '../../css/b/bsnu2pbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ztw2c0b2i"/><path clip-rule="evenodd" class="u_7ar5bnj"/><path class="bsnu2pbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lan-cable-solid" /></template>
