<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwml2jbca.css';
import '../../css/h/h1ouee4cg.css';
import '../../css/k/kj3-jsb-w.css';
import '../../css/s/sbe4o6bhg.css';
import '../../css/n/n8s4x7btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwml2jbca"/><path class="h1ouee4cg"/><path class="kj3-jsb-w"/><path class="sbe4o6bhg"/><path class="n8s4x7btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-pencil-ruler" /></template>
