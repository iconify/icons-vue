<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v4_papbth"/><path class="r4dzmma1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:login-blocked" /></template>
<style>
.r4dzmma1o {
  d: path("M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm1 2.25l4.5-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4_papbth {
  d: path("M12.084 20H5.5q-.147 0-.294-.014t-.291-.044q-.145-.028-.286-.071t-.277-.099q-.136-.057-.266-.126q-.13-.07-.253-.152q-.122-.081-.236-.175t-.218-.198t-.198-.218t-.175-.236q-.082-.123-.152-.253t-.126-.266t-.099-.277t-.071-.286q-.029-.144-.044-.291T2.5 17V7q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277t.126-.266t.152-.253t.175-.236t.198-.218t.218-.198q.114-.094.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071q.144-.029.291-.044T5.5 4h13q.147 0 .294.014t.291.044q.145.028.286.071t.277.099q.136.057.266.126q.13.07.253.152q.122.081.236.175t.218.198t.198.218t.175.236q.082.123.152.253t.126.266t.099.277t.071.286t.044.291T21.5 7v6.108M2.5 9h19M6 6.5h.01M9 6.5h.01");
}

</style>
