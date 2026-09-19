<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bip1gyzkx.css';
import '../../css/l/ll5ebi28y.css';
import '../../css/z/z2g23rxag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bip1gyzkx"/><path class="ll5ebi28y"/><path class="z2g23rxag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid19-virus-1" /></template>
