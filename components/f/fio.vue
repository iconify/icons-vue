<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gym54n37m"/><path class="hlq83_rmd"/><path class="uasum766t"/><path class="ectfxccpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fio" /></template>
<style>
.ectfxccpm {
  fill: var(--svg-color--00a0df, #00a0df);
  d: path("m8.573 11.775l4.77-2.446l-4.77-2.446a.24.24 0 0 0-.265 0a.95.95 0 0 0-.114.414v4.142q.004.137.056.266c.063.107.2.144.308.08z");
}

.ft5dv1b6b {
  fill: none;
}

.gym54n37m {
  fill: var(--svg-color--425cc7, #425cc7);
  d: path("M12.424 14.572v6.04c0 .32-.201.474-.45.339l-3.326-1.783a1.03 1.03 0 0 1-.453-.83v-5.903q.075.06.159.106z");
}

.hlq83_rmd {
  fill: var(--svg-color--005cb9, #005cb9);
  d: path("m8.573 11.776l6.859-3.517a.81.81 0 0 0 .377-.665V3.319c0-.265-.17-.387-.377-.281l-6.32 3.241c-.652.35-.954.515-.918 1.254v3.962c0 .252.173.387.38.28");
}

.uasum766t {
  fill: var(--svg-color--3cb4e5, #3cb4e5);
  d: path("m8.573 6.883l6.859 3.517c.23.146.37.396.377.668v4.272c0 .265-.17.39-.377.284l-6.859-3.518a.81.81 0 0 1-.379-.667V7.166c0-.261.173-.39.38-.283");
}

</style>
