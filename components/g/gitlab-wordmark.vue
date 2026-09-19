<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyukhkbwi.css';
import '../../css/n/nn68jobvu.css';
import '../../css/s/spqgtvbyi.css';
import '../../css/i/idse3ubex.css';
import '../../css/k/kloemtb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yyukhkbwi"/><path class="nn68jobvu"/><path class="spqgtvbyi"/><path class="idse3ubex"/><path class="kloemtb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gitlab-wordmark" /></template>
