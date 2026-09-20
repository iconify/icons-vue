<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u22x8cbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u22x8cbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:citation" /></template>
