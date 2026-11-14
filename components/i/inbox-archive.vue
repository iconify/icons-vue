<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b9u05ab8j"/><path class="c9d2xrbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inbox-archive" /></template>
<style>
.b9u05ab8j {
  d: path("M12.189 18H5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2.5 15.5V11l2.25-6.5q.04-.114.098-.221q.058-.106.133-.202q.074-.095.163-.178q.088-.082.189-.149q.101-.068.211-.118t.227-.082t.238-.044t.241-.006h9.5q.121-.007.241.006q.121.012.238.044t.227.082t.211.118t.189.149q.089.083.163.178q.075.096.133.202t.098.221L19.5 11v1.738");
}

.c9d2xrbqx {
  d: path("M2.5 11H7l1.5 2.5h3.685m1.77-.758L15 11h4.5M15 15.5h6.5v2H15Zm.75 2v3.25a.75.75 0 0 0 .75.75H20a.75.75 0 0 0 .75-.75V17.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
