<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ep0derb_u"/><path class="oxc-mbbgg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctx-background" /></template>
<style>
.ep0derb_u {
  fill: var(--svg-color--deb132, #deb132);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.oxc-mbbgg {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.565 11.868L5.75 13.213l1.469.679q.638-.36 1.255-.757c.408-.269.652-.112.776 0v2.746l-1 .672v2.088l-1 .392V20l1.761-.743V17.31l2.739-1.429v-1.135l3.563-1.401c.507-.762 1.333-1.196 1.682-1.317v2.045l-.745.427v1l1.5-.852v-4.133l-1.5.406V7.877l1.324.719l.676-2.004c-.046-.401-.538-.995-.835-.778c-.43.314.072.713.297.89l-.454.855L16.07 6.5h-.821v-.37c.21.022.45-.103.5-.168c.009-.13.022-.547 0-1.163c-.022-.617-.611-.789-.892-.799c-1.258-.01-.956 1.265-.608 1.691v.81h-1.118l-1.944 1.575c.228.356.723 1.145.88 1.454c.196.385.49.471.65.484c.16.012.487.037.56-.41c.059-.358-.457-.39-.722-.361l-.314-.897l1.113-.47l.651 2.477l-4.244 2.092z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
