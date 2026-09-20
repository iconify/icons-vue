<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="f5474tjgx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:forth-background" /></template>
<style>
.f5474tjgx {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.279 20v-.75c.26-.078.607-.055.883-.138l.182-.066c.276-.11.53-.298.717-.53a3.2 3.2 0 0 0 .342-.54c.138-.26.26-.53.37-.8c.22-.552.441-1.104.65-1.661l2.235-5.727c.717-1.854 1.38-3.697 2.108-5.545c.248-.072.469-.171.717-.243c.331.839.657 1.7.954 2.549c.982 2.78 1.965 5.556 2.969 8.32c.276.756.552 1.512.838 2.268q.24.66.602 1.263a1.7 1.7 0 0 0 1.015.745c.287.072.574.116.86.165V20h-6.063v-.695s.022-.022.072-.028c.237-.033.761-.077.993-.138q.21-.064.408-.165c.226-.127.32-.331.298-.59a2 2 0 0 0-.06-.348c-.05-.177-.11-.353-.166-.519a1315 1315 0 0 1-3.559-10.174c-.01-.038-.016-.077-.055-.11l-.033.022a.2.2 0 0 0-.022.055c-.574 1.672-1.186 3.327-1.788 4.983a148 148 0 0 0-1.318 3.685c-.166.497-.331.993-.486 1.495a4 4 0 0 0-.132.585a1.5 1.5 0 0 0-.011.403c.016.176.11.33.254.441c.303.22 1.418.348 1.743.425V20z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
