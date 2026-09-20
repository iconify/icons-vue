<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGxqDWoc8B)" class="g_oo9cb1o"/><path fill="url(#SVGxqDWoc8B)" class="ug6tpudvm"/><defs><linearGradient id="SVGxqDWoc8B" x1="12.59" x2="12.87" y1="2.72" y2="21.565" gradientUnits="userSpaceOnUse"><stop class="s9r4x3b3x"/><stop offset="1" class="rk74sxbvk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bnx" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_oo9cb1o {
  d: path("m11.45 3.565l-7.13 7.03c-.41.4-.575.9-.57 1.405a2 2 0 0 0 .57 1.405l7.13 7.035c.405.4.915.56 1.425.56s1.02-.16 1.425-.565l4.55-4.48c-1.17-.105-1.565.15-2.03.44c-.305.195-.645.41-1.25.55c-.305.07-.56.115-.77.115c-.515 0-.77-.175-.995-.33c-.175-.125-.325-.23-.565-.23h-2.65c.43-.66.14-.87.14-.87s-.92-.22-.705-2.505c-1.875-2.045-1.71-4.5-1.71-4.5s.625 2.02 3.42 3.095c-.12-1.54.305-2.15.5-2.42l.07-.115l.095.2c.255.56.61 1.34 2.47 1.77c.6-.75.835-.935 1.335-1.33l.095-.075c-.43-1.43-.355-2.225 0-2.815l.12.3c.4 1 1.04 2.61 3.83 2.195L14.3 3.565A1.98 1.98 0 0 0 12.875 3c-.51 0-1.02.16-1.425.565");
}

.rk74sxbvk {
  stop-color: var(--svg-color--ef2357, #ef2357);
}

.s9r4x3b3x {
  stop-color: var(--svg-color--f15f3e, #f15f3e);
}

.ug6tpudvm {
  d: path("M13.72 12.975c-.1.055-.2.1-.275.15c1.1.935 2.21-.815 1.71-1.125a6.1 6.1 0 0 1-1.435.975");
}

</style>
