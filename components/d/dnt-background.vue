<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="bmf9w4boz"/><path class="hpikozbqp"/><path class="w1nroc6ha"/><path class="za6nsibnw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dnt-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bmf9w4boz {
  fill: var(--svg-color--98f7d2, #98f7d2);
  d: path("M19.428 10.505a5.1 5.1 0 0 0-.556-1.493c-.54-.922-1.718-2.263-3.19-3.32c0 0-1.112-.738-1.636-.99c-1.913-.905-4.056-1.089-5.888.57c-3.075 2.802-4.612 6.709-3.075 10.599c.033.084.884 2.465 5.987 4.059c2.24.066 3.549-.068 4.988-.923c1.881-1.107 2.977-3.119 3.37-5.165c.114-.62.13-2.716 0-3.337");
}

.ft5dv1b6b {
  fill: none;
}

.hpikozbqp {
  fill: var(--svg-color--aff3f9, #aff3f9);
  d: path("M13.368 5.018v3.687l-3.937.25l-1.554 1.852l-.611 2.823l1.663 2.636l2.102.926h2.855l2.337-.456V6.112s-1.651-1.325-2.73-1.643");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w1nroc6ha {
  fill: var(--svg-color--2f3d86, #2f3d86);
  d: path("M18.413 14.261c-.588-.033-.261-.989-.523-2.079c-.31-1.207.147-2.046.752-2.012c.285.046.555.161.786.335a5.1 5.1 0 0 0-.556-1.492c-.54-.923-1.64-2.264-3.112-3.32v9.991c0 .44-.445.904-.856.998a1 1 0 0 1-1.119-.561a3.8 3.8 0 0 1-1.94.589c-2.114.059-4.078-1.495-4.075-3.793s1.847-4.033 3.96-4.038c.687-.002 1.085.104 1.68.457V5.454c-.003-.15.043-.3.105-.436a1 1 0 0 1 .27-.351c-1.914-.906-3.795-1.054-5.627.606c-3.075 2.801-4.612 6.708-3.075 10.598c.033.085.066.168.099.235a.8.8 0 0 1 .18-.252c.8-.838 1.684.873 3.565 1.861c1.194.622 1.881 1.444 2.143 2.215c1.75.218 3.549-.067 4.988-.923c1.881-1.107 2.977-3.119 3.37-5.165c-.28.252-.638.4-1.015.42m-6.41-7.947c.443-.017.851.52.867.77c.017.252-.375.152-.8.302c-.476.168-.819.017-.835-.234c-.017-.252.31-.822.769-.838");
}

.za6nsibnw {
  fill: var(--svg-color--2f3d86, #2f3d86);
  d: path("M11.05 14.192c.951.513 2.1.311 2.313-.84c.115-.668.05-1.71-.574-2.037c-2.068-1.12-3.808 1.758-1.74 2.877");
}

</style>
