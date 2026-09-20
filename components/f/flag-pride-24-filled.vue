<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n_b6nlb2f"/><path class="v45dur3wh"/><path class="bbrax_b8z"/><path class="s76leo46g"/><path class="mnuv5ibne"/><path class="nw5zm9q9z"/><path class="qlf4guowz"/><path class="dhai-tctv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-pride-24-filled" /></template>
<style>
.bbrax_b8z {
  fill: var(--svg-color--f36d38, #F36D38);
  d: path("M4 7.25h16V9H4z");
}

.dhai-tctv {
  d: path("M3.75 3a.75.75 0 0 0-.75.75v17.5a.75.75 0 0 0 1.5 0V16.5h15.75a.75.75 0 0 0 .75-.75v-12a.75.75 0 0 0-.75-.75H3.75zm.75 1.5h15V15h-15V4.5z");
  fill: var(--svg-color--212121, #212121);
}

.ft5dv1b6b {
  fill: none;
}

.mnuv5ibne {
  fill: var(--svg-color--61bc51, #61BC51);
  d: path("M4 10.5h16v1.75H4z");
}

.n_b6nlb2f {
  fill: var(--svg-color--745125, #745125);
  d: path("M4 4.25h16v1.5H4z");
}

.nw5zm9q9z {
  fill: var(--svg-color--1793e8, #1793E8);
  d: path("M4 12.25h16v1.5H4z");
}

.qlf4guowz {
  fill: var(--svg-color--b73fbb, #B73FBB);
  d: path("M4 13.75h17v1.5H4z");
}

.s76leo46g {
  fill: var(--svg-color--ffd23e, #FFD23E);
  d: path("M4 9h16v1.5H4z");
}

.v45dur3wh {
  fill: var(--svg-color--e62c46, #E62C46);
  d: path("M4 5.75h16v1.5H4z");
}

</style>
