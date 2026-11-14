<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3ik4sbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:highlight-color" /></template>
<style>
.c3ik4sbck {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.329 14.665l6-12q.067-.134.18-.232q.112-.097.254-.145q.141-.047.29-.036q.149.01.282.077q.109.055.195.141t.141.195l3.75 7.499v.001l2.25 4.5q.067.133.077.282q.011.149-.036.29q-.048.142-.145.254q-.098.113-.232.18q-.133.067-.282.077q-.149.011-.29-.036q-.142-.048-.254-.145q-.113-.098-.18-.232l-2.043-4.085H8.714l-2.043 4.085q-.067.134-.18.232q-.112.097-.254.145q-.141.047-.29.036q-.149-.01-.282-.077q-.066-.033-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137m9.207-4.915L12 4.677L9.464 9.75zM5.25 19.5q0-2.25 2.25-2.25h9q2.25 0 2.25 2.25t-2.25 2.25h-9q-2.25 0-2.25-2.25");
}

</style>
