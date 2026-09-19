<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj2raobmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bj2raobmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:corkscrew" /></template>
