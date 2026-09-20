<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_ay6bbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-style-guide-20-filled" /></template>
<style>
.a_ay6bbyn {
  fill: currentColor;
  d: path("M9.65 11.148a.5.5 0 0 1 .7 0l5.384 5.3A3 3 0 0 1 14 17H6a3 3 0 0 1-1.734-.551zM14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-.558 1.743l-5.39-5.308a1.5 1.5 0 0 0-2.105 0l-5.39 5.308A3 3 0 0 1 3 14v-3h2.5c.973 0 1.813-.557 2.227-1.369a2.5 2.5 0 0 0 2.15-1.837l1.035-3.863c.084-.313.102-.627.067-.93zM5.5 3A1.5 1.5 0 0 1 7 4.5v4A1.5 1.5 0 0 1 5.5 10h-3A1.5 1.5 0 0 1 1 8.5v-4A1.5 1.5 0 0 1 2.5 3zm7 3.25a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5M4.187 2a1.5 1.5 0 0 1 1.8-.946l2.898.776a1.5 1.5 0 0 1 1.06 1.838L8.91 7.532c-.13.482-.48.844-.914 1.01L8 8.5v-4c0-.556-.185-1.07-.493-1.485A2.5 2.5 0 0 0 5.499 2z");
}

</style>
