<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2r7qdbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-edit" /></template>
<style>
.t2r7qdbsd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm9.567 2.684q.512.512.512 1.237t-.513 1.239l-4.629 4.627q-.482.482-1.15.616l-.437.087q-.71.142-1.221-.369t-.369-1.22l.088-.439q.133-.667.614-1.149l4.629-4.629q.512-.513 1.238-.513q.725 0 1.237.512z");
}

</style>
