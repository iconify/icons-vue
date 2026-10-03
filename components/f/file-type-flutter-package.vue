<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cyqx2942o"><path class="l_s37ccyr"/><path class="zoc1sgeud"/><path class="oy636uowd"/><path class="zsxxgabgu"/><path class="r843flbyg"/></g><path class="ihork2b4r"/><path class="pguk__vir"/><path class="ef9asjg5d"/><path class="c9je-ebiw"/><path class="rwwx-rbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flutter-package" /></template>
<style>
.c9je-ebiw {
  fill: var(--svg-color--095a9d, #095a9d);
  d: path("m23.5 27.73l-2.41-2.4l3.26-3.24l5.57 5.64z");
}

.cyqx2942o {
  stroke-width: var(--svg-stroke-width--0-12px, 0.12px);
}

.ef9asjg5d {
  fill: var(--svg-color--1fbcfd, #1fbcfd);
  d: path("m21.05 18.94l-3.22 3.19l3.26 3.2l3.26-3.24z");
}

.ihork2b4r {
  fill: var(--svg-color--40d0fd, #40d0fd);
  d: path("m21.05 18.94l2.57-2.5H30l-5.65 5.65z");
}

.l_s37ccyr {
  fill: var(--svg-color--f2e6c9, #f2e6c9);
  d: path("m7.43 3.52l6.03-.01l-1.4 6.17h-9.2q-.44 0-.87-.02zm10.2-.01h6.02l5.43 6.15c-1.16.03-2.32 0-3.48.02h-6.57z");
}

.oy636uowd {
  fill: var(--svg-color--e7bf55, #e7bf55);
  d: path("M2 9.66q.44.03.87.02h9.18v6.51l.26.02h6.52l.2-.02V9.67h6.57q1.74.02 3.48 0v18.82H2z");
}

.pguk__vir {
  fill: var(--svg-color--41d0fd, #41d0fd);
  d: path("M23.62 6.7L13.04 17.26l3.21 3.28L30 6.7z");
}

.r843flbyg {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M3.98 22.37h9.06v3.49H3.98z");
}

.rwwx-rbpj {
  fill: var(--svg-color--0e5199, #0e5199);
  d: path("m23.1 23.33l-2.01 2l3.03-1z");
}

.zoc1sgeud {
  fill: var(--svg-color--efc75e, #efc75e);
  d: path("M13.46 3.51h4.17l1.4 6.16h-6.98z");
}

.zsxxgabgu {
  fill: var(--svg-color--dbb551, #dbb551);
  d: path("M12.05 9.68h6.98v6.52l-.2.01H12.3l-.25-.02z");
}

</style>
