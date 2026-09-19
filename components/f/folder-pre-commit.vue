<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzkxxlbjg.css';
import '../../css/q/qy_pj4bzp.css';
import '../../css/k/kqa5ceb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zzkxxlbjg"/><rect transform="rotate(-45.004)" class="qy_pj4bzp"/><path class="kqa5ceb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-pre-commit" /></template>
