<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/r/rcl4fqbef.css';
import '../../css/o/oi_k2iufm.css';
import '../../css/i/i4xym8b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="rcl4fqbef"/><path class="oi_k2iufm"/><path class="i4xym8b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-forgejo-open" /></template>
