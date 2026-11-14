<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n31dgzboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hook-knife" /></template>
<style>
.n31dgzboq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.607 11.864l.416-.697Q14.331 2.25 18.75 2.25q2.457 0 2.953 2.411q.432 2.097-1.089 4.269q-.042.061-.095.112q-.054.051-.116.09q-.062.04-.131.067t-.142.04q-.072.012-.146.011t-.146-.018t-.14-.045q-.068-.03-.128-.073q-.02-.013-.039-.028l-.969-.776q-1.938.644-6.193 6.864q-.061.088-.143.156q-.083.068-.182.11t-.205.055t-.212-.005q-.169.588-.635 1.053l-4.949 4.949q-.732.733-1.768.733q-1.035 0-1.767-.733q-.733-.732-.733-1.767q0-1.036.733-1.768l4.949-4.949q.465-.466 1.053-.635q-.022-.132.003-.263t.094-.246");
}

</style>
