<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlc5p2mlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlc5p2mlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bat" /></template>
