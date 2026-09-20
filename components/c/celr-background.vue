<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="y9wjm7qbz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:celr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9wjm7qbz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19 11.433c.127-.333.527-.433.853-.433H20v.667c-.187 0-.377-.007-.553.05a.7.7 0 0 0-.317.206c-.153.2-.117.337-.13.52v1.89h-1V11h1zM8.46 13.48c-.613.577-1.14.853-2.01.853c-1.45 0-2.45-.97-2.45-2.34c0-1.403 1.133-2.326 2.463-2.326c.774 0 1.51.326 2.017.89l-.62.78c-.42-.43-.877-.67-1.417-.67c-.9 0-1.48.583-1.443 1.326c.033.744.547 1.34 1.463 1.34c.574 0 .96-.223 1.4-.643zm3.667.123c-.367.5-.85.724-1.57.724c-1.09 0-1.89-.65-1.89-1.677c0-1.023.776-1.65 1.876-1.65c1.084 0 1.79.723 1.79 1.65V13H9.667c.083.49.4.667.89.667q.549.001.9-.334l.673.267zm-.794-1.27c0-.286-.3-.666-.823-.666c-.52 0-.843.4-.843.666zm1.334-2.666h1v4.666h-1zM17.45 13.6c-.367.503-.85.727-1.573.727c-1.087 0-1.877-.66-1.877-1.75c0-.897.777-1.577 1.877-1.577c1.083 0 1.79.77 1.79 1.833V13H15c.033.42.387.667.877.667c.342.013.676-.107.933-.334zm-.783-1.267c0-.26-.284-.666-.79-.666c-.504 0-.877.406-.877.666z");
}

</style>
