<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixetddbeg.css';
import '../../css/z/z4tn2nb1x.css';
import '../../css/r/rysw60b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixetddbeg"/><path class="z4tn2nb1x"/><path class="rysw60b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-syntax-open" /></template>
