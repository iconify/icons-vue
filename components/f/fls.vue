<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGu0zQeN5a)" class="s-i0zsb0r"/><path fill="url(#SVGu0zQeN5a)" class="tw-0jne2g"/><defs><linearGradient id="SVGu0zQeN5a" x1="21" x2="3" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="h75m_nbht"/><stop offset=".99" class="rsv_mlmew"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fls" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h75m_nbht {
  stop-color: var(--svg-color--5b8aff, #5b8aff);
}

.rsv_mlmew {
  stop-color: var(--svg-color--3f58ff, #3f58ff);
}

.s-i0zsb0r {
  d: path("M6.351 15.937c3.306.837 4.02 2.44 3.959 3.137l-3.96 1.924h-.787a2.55 2.55 0 0 1-2.559-2.531c0-1.4 1.147-2.53 2.559-2.53zm3.115.185l-6.405-3.16c-.45-2.666 1.67-3.25 3.2-3.205c.4.005.787.14 1.142.32c1.59.81 4.386 2.221 6.061 3.048c1.89.928 2.025 2.384 1.856 2.997l-4.206 2.064a3.7 3.7 0 0 0-1.648-2.064");
}

.tw-0jne2g {
  d: path("M14.73 12.478L3.005 6.658c0-2.925 2.16-3.656 3.324-3.656c.933 0 1.625.231 1.855.35c2.683 1.304 8.435 4.104 9.97 4.869C20.072 9.177 21 9.779 21 11.37c0 1.462-.619 2.21-1.198 2.508c-.894.455-2.378 1.192-3.12 1.496a3.68 3.68 0 0 0-1.952-2.896");
}

</style>
