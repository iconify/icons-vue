<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="td-ylib2n"/><path class="e-wg5wbdn"/><linearGradient id="SVGpIaA6dLg" x1="37.617" x2="86.158" y1="46.75" y2="46.75" gradientUnits="userSpaceOnUse"><stop offset="0" class="necgdbbfe"/><stop offset=".061" class="gbgww8wfp"/><stop offset=".147" class="ya-wayzpg"/><stop offset=".235" class="jss_lnbvx"/><stop offset=".323" class="um5oz6btz"/><stop offset=".414" class="iw8-jgb2j"/><stop offset=".509" class="kryztgb3r"/><stop offset=".609" class="i6o83mbor"/><stop offset=".696" class="aeqo7kbzg"/><stop offset=".777" class="hvqq2vhlh"/><stop offset=".856" class="cui69794b"/><stop offset=".931" class="ncwuz3baw"/><stop offset="1" class="necgdbbfe"/></linearGradient><path fill="url(#SVGpIaA6dLg)" class="zxbuncctx"/><path class="rqptrybcd"/><linearGradient id="SVGGYA1VApo" x1="44.427" x2="51.535" y1="117.96" y2="64.944" gradientUnits="userSpaceOnUse"><stop offset=".297" class="g3c_jbvil"/><stop offset="1" class="p2ze557dr"/></linearGradient><path fill="url(#SVGGYA1VApo)" class="zgot9lavo"/><linearGradient id="SVGnVDLYcwx" x1="82.779" x2="76.996" y1="120.125" y2="77.91" gradientUnits="userSpaceOnUse"><stop offset=".297" class="g3c_jbvil"/><stop offset="1" class="p2ze557dr"/></linearGradient><path fill="url(#SVGnVDLYcwx)" class="hnzkkyb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:dress" /></template>
<style>
.aeqo7kbzg {
  stop-color: var(--svg-color--72d3fe, #72d3fe);
}

.cui69794b {
  stop-color: var(--svg-color--47c3fa, #47c3fa);
}

.e-wg5wbdn {
  fill: var(--svg-color--1565c0, #1565c0);
  d: path("M82.54 6.8c.02-.81-.51-1.53-1.28-1.75l-3.46-.98c-1.02-.29-2.05.37-2.22 1.42l-1.71 10.55s-5.3.91-11.17 5.69l-.39-.01c-5.87-4.78-11.29-5.68-11.29-5.68L49.3 5.48a1.773 1.773 0 0 0-2.22-1.42l-3.46.98c-.78.22-1.31.94-1.28 1.75c.09 3.23.4 11.68 1.33 20.24c.95 8.76 3 17.7 2.72 20.85c0 0 8.04 1.1 15.81 1.18v.01h.52v-.01c7.76-.07 15.81-1.18 15.81-1.18c-.28-3.15 1.77-12.09 2.72-20.85c.89-8.56 1.2-17 1.29-20.23");
}

.g3c_jbvil {
  stop-color: var(--svg-color--0d47a1, #0d47a1);
}

.gbgww8wfp {
  stop-color: var(--svg-color--20b4f7, #20b4f7);
}

.hnzkkyb1a {
  d: path("M77.45 120.26c-2.45-15.11-3.92-30.15-3.21-42.35c0 0 5.55 22.99 13.52 38.73c0 0-2.71.39-5.3 1.29c-1.81.63-5.01 2.33-5.01 2.33");
}

.hvqq2vhlh {
  stop-color: var(--svg-color--60ccfc, #60ccfc);
}

.i6o83mbor {
  stop-color: var(--svg-color--7dd7ff, #7dd7ff);
}

.iw8-jgb2j {
  stop-color: var(--svg-color--7cd7ff, #7cd7ff);
}

.jss_lnbvx {
  stop-color: var(--svg-color--5dcbfc, #5dcbfc);
}

.kryztgb3r {
  stop-color: var(--svg-color--80d8ff, #80d8ff);
}

.ncwuz3baw {
  stop-color: var(--svg-color--27b7f7, #27b7f7);
}

.necgdbbfe {
  stop-color: var(--svg-color--03a9f4, #03a9f4);
}

.p2ze557dr {
  stop-color: var(--svg-color--0d47a1, #0d47a1);
  stop-opacity: 0.2;
}

.rqptrybcd {
  fill: var(--svg-color--0d47a1, #0d47a1);
  d: path("M73.82 16.09c-.84-.13-3.23.81-3.85 1.05c-2.73 1.05-4.99 2.5-7.16 4.45c-.01.01-.14.09-.3.09s-.27-.09-.28-.1c-2.17-1.95-4.45-3.38-7.18-4.43c-.63-.24-3.02-1.18-3.85-1.05c-1 .15.21 1.26 2.02 2.84c1.82 1.58 4.39 3.8 6.57 5.76c.75.67 1.75.97 2.72 1.05c.97-.08 1.97-.38 2.72-1.05c2.18-1.96 4.75-4.18 6.57-5.76s3.02-2.7 2.02-2.85");
}

.td-ylib2n {
  fill: var(--svg-color--1565c0, #1565c0);
  d: path("M89.71 68.54c-5.89-13.16-11.59-21.56-11.59-21.56v-.01H46.05c-1.91 3.74-5.11 9.81-9.71 18.28c-5.59 10.3-18.23 43.45-18.23 43.45s.74 4.38 11.5 6.35c7.14 1.31 9.29.19 15.26 3.43c5.27 2.86 8.92 5.53 17.85 5.53s11.18-2.21 18.45-5.53c6.19-2.83 9.53-1.45 16.64-2.91c15.07-3.09 16.06-14.11 16.06-14.11s-11.52-4.69-24.16-32.92");
}

.um5oz6btz {
  stop-color: var(--svg-color--71d2fe, #71d2fe);
}

.ya-wayzpg {
  stop-color: var(--svg-color--42c1fa, #42c1fa);
}

.zgot9lavo {
  d: path("M39.6 116.06c3.73-28.23 13.54-52.85 13.54-52.85s-3.28 29.02-4.01 57.59c0 0-2.85-1.8-5.46-2.95s-4.07-1.79-4.07-1.79");
}

.zxbuncctx {
  d: path("M63.2 50.16c-9.1 0-15.33-.74-17.45-.98a.78.78 0 0 1-.68-.87l.6-4.28a.77.77 0 0 1 .85-.67c2.03.22 8.09.79 16.68.79c8.26 0 13.23-.53 15-.75c.41-.05.79.23.86.64l.46 4.25c.07.43-.22.84-.66.9c-1.89.24-6.78.97-15.66.97");
}

</style>
