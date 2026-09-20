<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g2gxpcboc"/><path class="n9m39q2ye"/><path class="p3tzymmao"/><path class="u4fm1rnju"/><path class="gp2svq_ok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fold" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g2gxpcboc {
  fill: var(--svg-color--0cffff, #0cffff);
  d: path("M8.692 8.055A6.3 6.3 0 0 0 5.743 9.18a6.55 6.55 0 0 0-1.593 9.04a6.342 6.342 0 0 0 9.545 1.102h-.636c-3.472.034-6.59-2.802-6.68-6.275c-.05-1.851.895-3.691 2.313-4.991");
}

.gp2svq_ok {
  fill: var(--svg-color--0de4c1, #0de4c1);
  d: path("M16.51 9.46a6.4 6.4 0 0 1-.788 3.096a6 6 0 0 0-.338-1.407V5.813a6.46 6.46 0 0 1 1.126 3.653z");
}

.n9m39q2ye {
  fill: var(--svg-color--0bffff, #0bffff);
  d: path("M9.194 16.495c.636.822 1.485 1.21 2.515 1.672c3.292 1.463 7.187.067 8.7-3.113a6.25 6.25 0 0 0-3.218-8.402a7 7 0 0 0-.777-.287a6.13 6.13 0 0 1 1.221 3.855a6 6 0 0 1-.512 2.589a6.59 6.59 0 0 1-5.96 3.686z");
}

.p3tzymmao {
  fill: var(--svg-color--0de4c1, #0de4c1);
  d: path("M15.384 15.01a6.34 6.34 0 0 0 1.74-2.201c.382-.878.506-1.745.511-2.696c0-1.35-.394-2.673-1.221-3.748q.398.12.777.287c.213.096.242.107.444.22v11.08a5.8 5.8 0 0 1-2.25.732z");
}

.u4fm1rnju {
  fill: var(--svg-color--0cffff, #0cffff);
  d: path("M15.721 12.557a6.474 6.474 0 0 0-7.509-9.295a6.47 6.47 0 0 0-4.602 7.021A6.44 6.44 0 0 1 9.311 6.93c3.298 0 6.022 2.437 6.416 5.628z");
}

</style>
