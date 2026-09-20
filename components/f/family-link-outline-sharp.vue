<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg71o0ykc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:family-link-outline-sharp" /></template>
<style>
.cg71o0ykc {
  fill: currentColor;
  d: path("M9.75 23q-1.275 0-2.262-.763T6.15 20.276Q6 19.7 5.525 19.35T4.45 19q-.4 0-.75.163t-.6.462L1.575 18.35q.525-.65 1.288-1T4.45 17q1.275 0 2.275.75t1.35 1.975q.15.575.625.925t1.05.35q.475 0 .85-.25t.65-.625l.025-.05l-7.9-10.925L12.5.2l9.125 8.95L12.5 21.8q-.45.625-1.2.913T9.75 23m2.75-4.625l6.5-9L12.5 3L6.025 9.4zm.025-7.7");
}

</style>
