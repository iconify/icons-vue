<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jzvybmb9a"/><path class="b6ayisi1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corporate-law" /></template>
<style>
.b6ayisi1b {
  d: path("M6.75 21.5v-3h3v3m8.189-7.682l4.243 4.243l-2.121 2.121l-4.243-4.243ZM15.25 20.75L18 18");
}

.jzvybmb9a {
  d: path("M12.085 21.5H3.5v-13q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T5 7h1.5V4q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T8 2.5h1.5q.074 0 .147.007t.146.022t.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T11 4v3h.5q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T13 8.5v6.315m0 2.2v2M6.5 10.5V15m3.5-4.5V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
