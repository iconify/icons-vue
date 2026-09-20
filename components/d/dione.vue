<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f7eh1ltul"/><path class="auj-cdqpt"/><path class="nhn633b4i"/><path class="kyf13mo6g"/><path fill="url(#SVGdsoPMbVy)" class="r0a_zwb1m"/><defs><linearGradient id="SVGdsoPMbVy" x1="14.98" x2="7.415" y1="9.14" y2="15.185" gradientUnits="userSpaceOnUse"><stop class="f_idz2bjc"/><stop offset=".42" class="ncuebz6vy"/><stop offset=".65" class="lyl1xqb_w"/><stop offset="1" class="az_osfwxl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dione" /></template>
<style>
.auj-cdqpt {
  fill: var(--svg-color--7d1fa9, #7d1fa9);
  d: path("M12 19.41a7.41 7.41 0 1 0 0-14.821a7.41 7.41 0 0 0 0 14.82");
}

.az_osfwxl {
  stop-color: var(--svg-color--688feb, #688feb);
}

.f_idz2bjc {
  stop-color: var(--svg-color--6ddff4, #6ddff4);
}

.f7eh1ltul {
  fill: var(--svg-color--30128d, #30128d);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.ft5dv1b6b {
  fill: none;
}

.kyf13mo6g {
  fill: var(--svg-color--e7b2f8, #e7b2f8);
  d: path("M12 17.16a5.16 5.16 0 1 0 0-10.32a5.16 5.16 0 0 0 0 10.32");
}

.lyl1xqb_w {
  stop-color: var(--svg-color--20dffb, #20dffb);
}

.ncuebz6vy {
  stop-color: var(--svg-color--10fdf7, #10fdf7);
}

.nhn633b4i {
  fill: var(--svg-color--fb88f3, #fb88f3);
  d: path("M12 17.604a5.605 5.605 0 1 0 0-11.21a5.605 5.605 0 0 0 0 11.21");
}

.r0a_zwb1m {
  d: path("M16.56 12.17c0 2.6-1.74 3.75-4.295 4.405c-1.135.295-2.085.165-2.915 0c-1.33-.265-2.045-1.2-2.435-2.5a3.3 3.3 0 0 1-.105-.99c0-1.885 2.46-5.61 5.05-5.61a4.7 4.7 0 0 1 4.7 4.7z");
}

</style>
