<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g8_2-obgx.css';
import '../../css/n/n_gojf7ke.css';
import '../../css/u/un4ldubvn.css';
import '../../css/c/caqvjbcca.css';
import '../../css/c/c2lbokb9y.css';
import '../../css/j/japywmblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g8_2-obgx"/><path class="n_gojf7ke"/><path class="un4ldubvn"/><path class="caqvjbcca"/><path class="c2lbokb9y"/><path class="japywmblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:confetti2-duotone" /></template>
