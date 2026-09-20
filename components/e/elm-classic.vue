<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x7fjqrbee"/><path class="jmqgxtb3w"/><path class="eugjv3bjh"/><path class="a8a2av-of"/><path class="gmnme03xt"/><path class="fl6wkhz5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:elm-classic" /></template>
<style>
.a8a2av-of {
  fill: var(--svg-color--5fb4cb, #5fb4cb);
  d: path("M256 113.806V0H142.193z");
}

.eugjv3bjh {
  fill: var(--svg-color--596277, #596277);
  d: path("M120.978 128L0 7.022V248.98z");
}

.fl6wkhz5d {
  fill: var(--svg-color--eea400, #eea400);
  d: path("m128 120.979l55.322-55.323H72.677z");
}

.gmnme03xt {
  fill: var(--svg-color--8cd636, #8cd636);
  d: path("m195.584 67.434l60.288 60.289l-60.563 60.564l-60.289-60.289zM7.021 0l55.725 55.726h121.129L128.15 0z");
}

.jmqgxtb3w {
  fill: var(--svg-color--eea400, #eea400);
  d: path("M202.332 195.311L256 248.98V141.643z");
}

.x7fjqrbee {
  fill: var(--svg-color--5fb4cb, #5fb4cb);
  d: path("M128 135.022L7.023 256h241.955z");
}

</style>
