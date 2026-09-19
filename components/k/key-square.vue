<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rz3p3kv0u.css';
import '../../css/o/omeeehbxv.css';
import '../../css/u/u760mxb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rz3p3kv0u"/><path clip-rule="evenodd" class="omeeehbxv"/><path class="u760mxb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:key-square" /></template>
