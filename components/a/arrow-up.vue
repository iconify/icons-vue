<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v0g_z_j1d.css';
import '../../css/y/yynt2ibtm.css';
import '../../css/b/bhrwz6oki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="v0g_z_j1d"/><path class="yynt2ibtm"/><path class="bhrwz6oki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-up" /></template>
