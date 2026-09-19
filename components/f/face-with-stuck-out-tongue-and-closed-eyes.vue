<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="matrix(1 0 0 .99955 0 .229)" class="mopbmmb9p"><circle class="mn25m45ee"/><circle class="dpcafhb_v"/></g><path id="SVG3v28qb1i" class="gjxddabhi"/><path id="SVGvkxv1cJj" class="n4mb-sb4p"/><use href="#SVG3v28qb1i"/><path class="tso_qvh7j"/><use href="#SVGvkxv1cJj"/><path class="i341nx0gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:face-with-stuck-out-tongue-and-closed-eyes" /></template>
<style>
.dpcafhb_v {
  cx: 31.749px;
  cy: 32.08px;
  r: 31.723px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

.gjxddabhi {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M51.681 38.825c0 10.915-8.855 19.772-19.774 19.772c-10.911 0-19.768-8.857-19.768-19.772");
}

.i341nx0gg {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M29.05 28.21c-3.03-4.98-9.168-8.04-14.989-8.217c-2.01-.062-2 2.999 0 3.061c2.793.087 5.706 1.023 8.138 2.599c-.118.202-.279 2.527-.198 2.715c-2.861.34-5.737.584-8.551 1.244c-1.952.458-1.124 3.41.831 2.952c4.557-1.069 9.28-1.037 13.837-2.106c.98-.23 1.436-1.419.932-2.248m6.33 2.247c4.558 1.069 9.283 1.037 13.838 2.106c1.956.458 2.785-2.494.831-2.952c-2.814-.66-5.69-.904-8.549-1.244c.079-.188-.08-2.513-.2-2.715c2.434-1.576 5.345-2.511 8.14-2.599c2.01-.062 2.01-3.123 0-3.061c-5.822.179-11.963 3.237-14.99 8.217c-.506.83-.048 2.02.93 2.248");
}

.mn25m45ee {
  cx: 31.749px;
  cy: 31.494px;
  r: 31.723px;
}

.mopbmmb9p {
  fill: var(--svg-color--fbb041, #fbb041);
}

.n4mb-sb4p {
  fill: var(--svg-color--fff, #fff);
  d: path("M48.29 40.812c0 4.359-7.487 7.899-16.717 7.899c-9.223 0-16.712-3.54-16.712-7.899");
}

.tso_qvh7j {
  fill: var(--svg-color--f45ba1, #f45ba1);
  d: path("M42.641 56.54c0 4.03-4.553 7.305-10.166 7.305s-10.166-3.271-10.166-7.305l2.193-8.425c0-4.03 2.36-7.304 7.973-7.304s7.972 3.271 7.972 7.304z");
}

</style>
