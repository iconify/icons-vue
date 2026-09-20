<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y5_4jjaaj"/><path class="infzn8b9e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:inst-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.infzn8b9e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.828 19.996c-.457.047-.828-.33-.828-.795v-2.212c0-.46.376-.828.823-.917a4.24 4.24 0 0 0 3.411-4.074a4.24 4.24 0 0 0-3.41-4.075C12.37 7.83 12 7.467 12 7.01V4.794c0-.46.371-.837.828-.79a8.02 8.02 0 0 1 7.17 7.994c0 4.159-3.143 7.575-7.17 7.998M8.565 4.776c.518-.25 1.082.15 1.082.715v13.004c0 .565-.564.965-1.082.715a8.03 8.03 0 0 1-4.564-7.212c0-3.167 1.859-5.905 4.564-7.218z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y5_4jjaaj {
  fill: var(--svg-color--3f75ff, #3f75ff);
  d: path("M24 0H0v24h24z");
}

</style>
