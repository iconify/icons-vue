<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k128xnb9r"/><path class="o32_hh57m"/><path class="z0h67pq4l"/><path class="mpx95y60u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-storyboard" /></template>
<style>
.k128xnb9r {
  fill: var(--svg-color--ffcf31, #ffcf31);
  d: path("M16.271 9.616a5.137 5.137 0 1 0 5.137 5.137a5.137 5.137 0 0 0-5.137-5.137m0 7.379a2.231 2.231 0 1 1 2.229-2.231A2.23 2.23 0 0 1 16.271 17Z");
}

.mpx95y60u {
  fill: var(--svg-color--e9ad0f, #e9ad0f);
  d: path("m26.926 27.726l-.441-.44l2.634-2.634l-2.621-2.621l.441-.44L30 24.652z");
}

.o32_hh57m {
  fill: var(--svg-color--e9ad0f, #e9ad0f);
  d: path("M16.271 20.176a5.423 5.423 0 1 1 5.423-5.423a5.43 5.43 0 0 1-5.423 5.423m0-10.275a4.852 4.852 0 1 0 4.852 4.852A4.86 4.86 0 0 0 16.271 9.9Zm0 7.379a2.517 2.517 0 1 1 2.517-2.517a2.52 2.52 0 0 1-2.517 2.518Zm0-4.463a1.946 1.946 0 1 0 1.946 1.946a1.95 1.95 0 0 0-1.946-1.945Z");
}

.z0h67pq4l {
  fill: var(--svg-color--e9ad0f, #e9ad0f);
  d: path("M16.582 9.616h-.623v-.361A4.364 4.364 0 0 0 11.6 4.9H2v-.626h9.6a4.987 4.987 0 0 1 4.982 4.982Zm4.359 15.361a4.98 4.98 0 0 1-4.982-4.982V19.9h.623v.094a4.36 4.36 0 0 0 4.359 4.359h8.617v.623z");
}

</style>
