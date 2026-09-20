<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdm7i77zj.css';
import '../../css/k/kmqnegc2d.css';
import '../../css/c/ckfqb96yg.css';
import '../../css/v/vpbxhdc1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pdm7i77zj"/><circle class="kmqnegc2d"/><circle class="ckfqb96yg"/><circle class="vpbxhdc1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cluster-open" /></template>
