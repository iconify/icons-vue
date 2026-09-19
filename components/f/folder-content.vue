<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzkxxlbjg.css';
import '../../css/a/a5g1qzb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zzkxxlbjg"/><path class="a5g1qzb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-content" /></template>
