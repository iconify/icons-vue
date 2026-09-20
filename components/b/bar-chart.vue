<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGBaWlsbDK" class="jp9y0qb2k"/></defs><use href="#SVGBaWlsbDK" class="i2v6ey-hu"/><defs><path id="SVG59JHnW5y" class="ogp48sbsd"/></defs><use href="#SVG59JHnW5y" class="wok4wpqzw"/><defs><path id="SVGVrgVYbUm" class="zly-evbhm"/></defs><use href="#SVGVrgVYbUm" class="j71m3fb1u"/><path class="nacd_yo0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:bar-chart" /></template>
<style>
.i2v6ey-hu {
  fill: var(--svg-color--ed6c30, #ed6c30);
}

.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.jp9y0qb2k {
  d: path("M37.4 13.08c0-1.72-1.4-3.13-3.12-3.13H22.65c-1.72 0-3.12 1.41-3.12 3.13v112.17H37.4z");
}

.nacd_yo0i {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M122.63 128H2.76C1.23 128 0 126.77 0 125.24V6.18a2.76 2.76 0 0 1 2.76-2.76a2.75 2.75 0 0 1 2.75 2.76v116.31h117.12a2.76 2.76 0 0 1 2.76 2.76c0 1.52-1.24 2.75-2.76 2.75");
}

.ogp48sbsd {
  d: path("M73.09 50.56c0-1.72-1.4-3.13-3.12-3.13H58.35c-1.72 0-3.13 1.41-3.13 3.13v74.69h17.87z");
}

.wok4wpqzw {
  fill: var(--svg-color--006ca2, #006ca2);
}

.zly-evbhm {
  d: path("M108.79 30.71c0-1.72-1.41-3.13-3.13-3.13H94.03c-1.71 0-3.12 1.41-3.12 3.13v94.53h17.87V30.71z");
}

</style>
