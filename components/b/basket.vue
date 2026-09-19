<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tjn30lbcn.css';
import '../../css/d/d8d6hu87u.css';
import '../../css/s/sc-zjlc7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="tjn30lbcn"/><path class="d8d6hu87u"/><path class="sc-zjlc7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:basket" /></template>
