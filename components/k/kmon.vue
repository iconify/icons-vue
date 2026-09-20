<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xpxc5nfoz"/><path fill="url(#SVGb3GEBeUy)" class="id2unf_1s"/><defs><linearGradient id="SVGb3GEBeUy" x1="13.59" x2="2.475" y1="19.2" y2="18.382" gradientUnits="userSpaceOnUse"><stop offset=".15" class="pd9othbcg"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kmon" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.id2unf_1s {
  d: path("M12.53 18.685v1.543h-.01c-7.848 0-9.52-8.887-9.52-8.887l1.337-.37c0 1.975 2.808 7.714 7.936 7.714z");
}

.pd9othbcg {
  stop-color: var(--svg-color--f231af, #f231af);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.xpxc5nfoz {
  fill: var(--svg-color--f231af, #f231af);
  d: path("m10.096 13.296l1.014 2.865a.74.74 0 0 0 .925.432a.677.677 0 0 0 .458-.864l-.802-2.237l4.484 2.042c.386.175.85.03 1.034-.33a.704.704 0 0 0-.35-.966l-4.603-2.099l2.29-3.703c.205-.35.066-.792-.33-.977s-.9-.062-1.11.288l-2.192 3.549l-.679-1.913a.74.74 0 0 0-.92-.433c-.376.119-.587.5-.463.865l.493 1.388v.026c-.02.669-.246 1.286-.915 1.286c-1.198 0-1.198-2.037-1.198-2.623c0-.582.437-4.542 5.487-4.542c5.056 0 6.733 4.32 6.733 6.758s-1.878 6.578-7.067 6.578c-.134 0-1.1 1.543.247 1.543c4.536 0 8.368-3.692 8.368-8.254c0-1.08-.32-4.038-2.983-6.25a7.78 7.78 0 0 0-5.23-1.954c-2.017 0-3.663.746-4.743 1.58c-2.263 1.748-2.397 4.402-2.397 4.9c0 1.189.684 3.807 2.737 3.807a2.06 2.06 0 0 0 1.712-.762");
}

</style>
