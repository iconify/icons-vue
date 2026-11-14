<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncm9zd3bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compass-drafting-circle" /></template>
<style>
.ncm9zd3bu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 4.5q0-2.25 2.25-2.25t2.25 2.25q0 1.636-1.189 2.082l4.834 11.426q.991-.476 1.928-1.125q.061-.042.129-.071q.068-.03.14-.045q.072-.016.146-.017t.146.012q.073.013.142.041q.068.027.131.067q.062.04.115.091q.053.052.095.112t.071.129q.03.068.045.14q.016.072.017.146t-.012.146q-.013.073-.041.142q-.027.068-.067.131q-.04.062-.091.115q-.052.053-.112.095q-3.916 2.709-8.677 2.709t-8.677-2.709q-.122-.085-.203-.21q-.081-.126-.108-.273q-.027-.146.005-.292q.031-.146.116-.269q.042-.06.095-.112q.053-.051.115-.091t.131-.067t.142-.041t.146-.012t.146.017t.14.045q.068.029.129.071q.937.649 1.928 1.125l4.834-11.426Q9.75 6.136 9.75 4.5M12 7.925L7.492 18.581q2.138.745 4.508.745t4.508-.745z");
}

</style>
