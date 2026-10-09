<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umoge2bql.css';
import '../../css/l/lex5nub6o.css';
import '../../css/f/fp-kn4xoc.css';
import '../../css/w/wvq9wacvk.css';
import '../../css/b/ba4bo3btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="umoge2bql"/><path class="lex5nub6o"/><path class="fp-kn4xoc"/><path class="wvq9wacvk"/><path class="ba4bo3btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-flow-48-bold" /></template>
