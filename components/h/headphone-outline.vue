<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd1xwpbcc.css';
import '../../css/k/kcckbrb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd1xwpbcc"/><path clip-rule="evenodd" class="kcckbrb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:headphone-outline" /></template>
