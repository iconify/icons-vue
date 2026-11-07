<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxcwapovt.css';
import '../../css/c/cn3vjbcnl.css';
import '../../css/c/cpsdjbhjl.css';
import '../../css/q/q1sggqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxcwapovt"/><path class="cn3vjbcnl"/><path class="cpsdjbhjl"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-circle-outline" /></template>
