<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7l54zb3f.css';
import '../../css/i/ijxvr0blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c7l54zb3f"/><path class="ijxvr0blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-constant" /></template>
