<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1sv60b0b.css';
import '../../css/j/jls6yjbxr.css';
import '../../css/j/j_dws6b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f1sv60b0b"/><path class="jls6yjbxr"/><path class="j_dws6b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:angle-grinder-48-bold" /></template>
