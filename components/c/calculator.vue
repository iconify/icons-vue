<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t368qs-ir.css';
import '../../css/a/ab8ps0cuk.css';
import '../../css/z/ztqb5-nue.css';
import '../../css/u/urxus9vuq.css';
import '../../css/d/dk9x-4byk.css';
import '../../css/w/waov_dbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="t368qs-ir"/><path class="ab8ps0cuk"/><path class="ztqb5-nue"/><path class="urxus9vuq"/><path class="dk9x-4byk"/><path class="waov_dbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:calculator" /></template>
