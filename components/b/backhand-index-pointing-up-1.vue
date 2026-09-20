<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke1-0sh6u.css';
import '../../css/n/n0qm8zbwd.css';
import '../../css/t/tbzygubyy.css';
import '../../css/u/uymgdabjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ke1-0sh6u"/><path class="n0qm8zbwd"/><path class="tbzygubyy"/><path class="uymgdabjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:backhand-index-pointing-up-1" /></template>
