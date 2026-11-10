<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dp9rsbbnp"/><path class="haxo1bqmo"/><path class="u7fo3w5wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bubbles-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dp9rsbbnp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.5 8C15.3378 8 16.9178 9.106 17.6167 10.685L17.6973 10.888C17.7256 10.959 17.7922 11.008 17.8691 11.014C20.7344 11.204 23 13.587 23 16.5C23 19.538 20.5376 22 17.5 22C14.5867 22 12.2038 19.734 12.0137 16.869C12.0084 16.792 11.9595 16.725 11.8877 16.696L11.6865 16.617L11.3926 16.475C9.9695 15.719 9 14.224 9 12.5C9 10.015 11.0147 8 13.5 8ZM4 11C5.6568 11 7 12.343 7 14C7 15.657 5.6568 17 4 17C2.3432 17 1 15.657 1 14C1 12.343 2.3432 11 4 11Z");
}

.haxo1bqmo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.5 2C8.433 2 10 3.567 10 5.5C10 7.433 8.433 9 6.5 9C4.567 9 3 7.433 3 5.5C3 3.567 4.567 2 6.5 2Z");
}

.u7fo3w5wl {
  d: path("M17.5 11C20.5376 11 23 13.462 23 16.5C23 19.538 20.5376 22 17.5 22C14.4624 22 12 19.538 12 16.5C12 16.286 12.0132 16.065 12.0376 15.855L12.0703 15.607C12.4616 13.212 14.4006 11.338 16.8271 11.041C16.8345 11.04 16.8415 11.038 16.8486 11.036H16.8711C16.8783 11.036 16.8855 11.036 16.8926 11.035C17.0936 11.013 17.2967 11 17.5 11Z");
}

</style>
