<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzkxxlbjg.css';
import '../../css/t/t_2lkqbxb.css';
import '../../css/h/hablheomi.css';
import '../../css/c/c_g70-55x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zzkxxlbjg"/><g class="t_2lkqbxb"><path class="hablheomi"/><path class="c_g70-55x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-caddy" /></template>
