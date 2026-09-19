<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmf_k48cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmf_k48cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-alt-04" /></template>
