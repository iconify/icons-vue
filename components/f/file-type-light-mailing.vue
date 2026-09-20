<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><mask id="SVGQplcGdke" width="22.34" height="8.56" x="4.83" y="21.4" maskUnits="userSpaceOnUse"><path class="e9f03kbak"/></mask></defs><g mask="url(#SVGQplcGdke)" class="d2kvgvbvc"><path class="rf7hs7s8m"/><path class="kq4cltbbe"/></g><circle class="z81ar94gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-mailing" /></template>
<style>
.d2kvgvbvc {
  fill-rule: evenodd;
}

.e9f03kbak {
  fill: var(--svg-color--c4c4c4, #c4c4c4);
  d: path("M4.83 25.5h22.34v4.47H4.83z");
}

.kq4cltbbe {
  d: path("M23 23.63a2.05 2.05 0 1 0 2 2.05a2 2 0 0 0-2-2.05m0-2.23a4.28 4.28 0 1 0 4.21 4.28A4.24 4.24 0 0 0 23 21.4M9 23.63a2.05 2.05 0 1 0 2 2.05a2 2 0 0 0-2-2.05m0-2.23a4.28 4.28 0 1 0 4.21 4.28A4.24 4.24 0 0 0 9 21.4");
}

.rf7hs7s8m {
  d: path("M16 23.63a2.05 2.05 0 1 0 2 2.05a2 2 0 0 0-2-2.05m0-2.23a4.28 4.28 0 1 0 4.21 4.28A4.24 4.24 0 0 0 16 21.4");
}

.z81ar94gg {
  cx: 16px;
  cy: 12.65px;
  r: 10.61px;
}

</style>
