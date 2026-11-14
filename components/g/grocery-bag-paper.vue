<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5sftb3jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grocery-bag-paper" /></template>
<style>
.z5sftb3jv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 2.75H5q-.071 0-.141.013q-.07.014-.136.04q-.067.027-.127.065t-.111.087t-.094.107q-.041.058-.071.122q-.03.065-.048.134q-.017.069-.021.14l-1 18l-.001.042q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16l.042-.001q.073-.004.145-.023q.071-.018.138-.05t.126-.076q.059-.045.108-.1t.087-.119q.037-.063.062-.133q.024-.07.035-.143q.01-.073.006-.147l-1-18q-.004-.071-.021-.14t-.048-.134t-.071-.122q-.042-.058-.094-.107q-.051-.049-.111-.087t-.127-.065t-.136-.04T19 2.75h-4.5q-.167 0-.318.071t-.258.199L12 5.328L10.076 3.02q-.107-.128-.258-.199T9.5 2.75M6.75 13.625q0-3.375 3.375-3.375h3.75q3.375 0 3.375 3.375v.75q0 3.375-3.375 3.375h-3.75q-3.375 0-3.375-3.375z");
}

</style>
