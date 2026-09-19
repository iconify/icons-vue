<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgzdgcqyr.css';
import '../../css/j/jmo8dnbwh.css';
import '../../css/k/ki-cu7x0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hgzdgcqyr"/><path class="jmo8dnbwh"/><path class="ki-cu7x0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:haskell-wordmark" /></template>
