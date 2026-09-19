<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r2ofn9zof.css';
import '../../css/t/t07u0zb9p.css';
import '../../css/z/z5spejdbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r2ofn9zof"/><path class="t07u0zb9p"/><path class="z5spejdbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:basketball-hoop" /></template>
