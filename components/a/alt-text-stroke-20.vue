<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfe6msdjj.css';
import '../../css/c/cm27p2byo.css';
import '../../css/z/zfvicoeco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cfe6msdjj"/><path class="cm27p2byo"/><path class="zfvicoeco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alt-text-stroke-20" /></template>
