<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu6kif3au.css';
import '../../css/t/ttjmg5b9p.css';
import '../../css/g/gwclx3y4g.css';
import '../../css/f/fom3xqb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fu6kif3au"/><path class="ttjmg5b9p"/><path class="gwclx3y4g"/><path class="fom3xqb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dbackup-light" /></template>
