<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<linearGradient id="SVGWNkbddBL" x2="0" y1=".49" y2="-.27"><stop class="qnalmybfl"/><stop offset="1" class="cx6f0elvq"/></linearGradient><g transform="scale(.052)"><path class="s38tsubwv"/><ellipse class="itjop29jh"/><path fill="url(#SVGWNkbddBL)" class="xigwqmb5k"/><path class="ue1da7bzm"/><path class="kjwmusbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-robotcode" /></template>
<style>
.cx6f0elvq {
  stop-color: var(--svg-color--37ae71, #37ae71);
  stop-opacity: 0;
}

.itjop29jh {
  cx: 308px;
  cy: 161px;
  fill: var(--svg-color--36ae71, #36ae71);
  fill-opacity: var(--svg-fill-opacity--0-46, 0.46);
  rx: 53px;
  ry: 25px;
}

.kjwmusbbn {
  fill: var(--svg-color--004e44, #004e44);
  d: path("M244 250c0-17 13-31 29-31s29 14 29 31c0 6-5 11-10 11a11 11 0 0 1-11-11a8 8 0 0 0-8-9a8 8 0 0 0-8 9c0 6-5 11-11 11a11 11 0 0 1-10-11m121 38c0 6-5 11-11 11h-98a11 11 0 0 1-11-11c0-6 5-11 11-11h98c6 0 11 5 11 11m-46-32a12 12 0 0 1 3-16l24-17c5-3 12-2 15 3a12 12 0 0 1-3 16l-24 17l-6 2a12 12 0 0 1-9-5m123-49c-2 0-2 0 1 6c5 14 4 65-2 79c-4 8-4 9 7 12c46 16 39 85-9 85c-13 0-13 0-45-18c-27-16-26-9-45 2c-23 14-29 22-17 37c5 7 6 8 10 7c18-15 28-14 47-3c33 17 53 20 75 13c71-23 75-121 7-155c-5-3-5-3-5-6c4-24 3-34-4-46c-5-7-14-13-20-13m-137-90a119 119 0 0 0-107 68c-11 23-13 89-4 109c8 17 14 22 67 51l6 4c1 3-72 44-80 45c-54 11-72-67-19-84c7-3 8-4 5-12c-4-10-4-12-4-42c0-26 0-29 2-35c2-9 2-9-4-7c-17 6-25 30-19 58c0 4 0 4-6 7c-84 43-44 173 49 156a135 135 0 0 0 44-20l135-80c54-32 54-32 55-84c1-56-5-73-35-101a119 119 0 0 0-85-33m6 27c15 0 31 5 45 13c7 4 7 5-4 8l-1 1c-12 4-25 10-35 16s-7 6-21-2l-36-17c-6-1-5-3 6-9a96 96 0 0 1 46-10m-74 43c11 0 27 7 51 20c19 11 19 11 35 2c31-17 59-26 67-20c10 8 11 13 11 54c0 43 0 43-18 53l-61 34l-11 7h-8l-23-13c-74-41-66-33-67-79c0-41 4-59 24-58");
}

.qnalmybfl {
  stop-color: var(--svg-color--37ae71, #37ae71);
}

.s38tsubwv {
  fill: var(--svg-color--e9e9e2, #e9e9e2);
  d: path("m311 337l11-7l61-34c18-10 18-10 18-53c0-41-1-45-11-54c-8-6-36 3-67 20c-16 9-16 9-35-1c-24-14-40-21-52-21c-18-1-23 17-23 58c1 47-7 38 67 79l23 12q4 2 8 1");
}

.ue1da7bzm {
  fill: var(--svg-color--fff, #fff);
  d: path("M270 171a14 9-23 1 1 26-11a14 9-23 1 1-26 11");
}

.xigwqmb5k {
  d: path("M453 214s-11-2-9 0a47 47 0 0 1 18 32c1 9 9 10 12 10l21 11c88 60 46 198-59 194c-20-1-26-3-63-23c-14-8-40-23-35-23c11 1-25-13 12-36c7-5-6-5-69 40c-73 52-97 49-135 37c-92-27-98-163-9-198c7-3 8-3 15-8c15-11 1-26 9-29c22-10 0-7-10-5A145 145 0 0 0 45 399c22 68 87 108 153 96c21-3 44-16 102-50c6-3 9-2 10 0l66 35c85 44 177 0 198-96c16-73-37-153-110-168l-10-2z");
}

</style>
