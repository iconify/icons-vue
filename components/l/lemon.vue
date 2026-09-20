<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="oitzoi4mq"/><path class="hv8m-qbhk"/><path class="n22ilmbsr"/><path class="shzbu4beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:lemon" /></template>
<style>
.hv8m-qbhk {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M15.001 16a1 1 0 0 1-.801-.4c-.687-.916-1.308-1.955-1.965-3.056C9.967 8.749 7.396 4.446.783 2.976a1 1 0 1 1 .434-1.952C8.671 2.68 11.599 7.581 13.952 11.519c.63 1.054 1.224 2.049 1.848 2.881a1 1 0 0 1-.799 1.6");
}

.n22ilmbsr {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M34.3 31.534c.002-.017-.003-.028-.003-.043c2.774-5.335 2.647-15.113-3.346-21.107c-5.801-5.8-13.68-5.821-18.767-4.067c-1.579.614-2.917.066-3.815.965c-.881.881-.351 2.719-.714 3.819c-3.169 5.202-3.405 13.025 2.688 19.117c4.962 4.962 10.438 6.842 19.98 4.853q.003-.002.008-.002c1.148-.218 2.95.523 3.566-.094c1.085-1.085.309-2.358.403-3.441");
}

.oitzoi4mq {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M11.405 3.339c6.48-1.275 8.453 1.265 11.655.084s.093 2.82-.745 3.508c-.84.688-8.141 4.809-11.307 3.298s-3.182-6.186.397-6.89");
}

.shzbu4beb {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M8.208 6.583s-4.27-.59-6.857 4.599c-2.587 5.188.582 9.125.29 12.653c-.293 3.53 1.566 1.265 2.621-.445s4.23-4.895 4.938-9.269c.707-4.376-.07-6.458-.992-7.538");
}

</style>
