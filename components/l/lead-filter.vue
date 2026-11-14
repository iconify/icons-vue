<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2z2s_bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lead-filter" /></template>
<style>
.b2z2s_bte {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m8.288 7.628q.202-.386.459-.68q-1.761-.698-3.997-.698q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h11.674Q15 20.386 15 19.131v-.256l-.77-1.112q-1.043-1.51-.192-3.135m2.688-.378h2.298q1.08.001 1.581.957q.501.957-.113 1.844l-.858 1.241q-.134.193-.134.427v1.273q0 .769-.665 1.154q-.664.386-1.332.005l-.119-.068q-1.134-.647-1.134-1.953v-.411q0-.234-.133-.427l-.859-1.24q-.614-.888-.113-1.845q.501-.956 1.58-.957zm.001 1.5h-.001q-.172.001-.252.153q-.08.153.018.295l.857 1.24q.401.578.401 1.281v.411q0 .354.25.562v-.973q0-.703.4-1.281l.858-1.239q.098-.143.018-.296t-.252-.153z");
}

</style>
