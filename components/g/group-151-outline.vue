<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfdi3-zsx.css';
import '../../css/l/lvrxp9btv.css';
import '../../css/j/jkhrtccjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfdi3-zsx"/><path class="lvrxp9btv"/><path clip-rule="evenodd" class="jkhrtccjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:group-151-outline" /></template>
