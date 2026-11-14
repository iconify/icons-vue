<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzvkjcq4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:feldspar" /></template>
<style>
.xzvkjcq4u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.2 6.15l2.25-3q.675-.9 1.8-.9h3.5q1.125 0 1.8.9l2.25 3q.099.131.176.27q-.101-.082-.223-.126q-.123-.044-.253-.044h-11q-.13 0-.253.044q-.122.044-.223.126q.077-.139.176-.27m5.05 1.6H6.5q-.063 0-.124-.01q-.062-.011-.121-.031q-.059-.021-.114-.05t-.104-.069q-.049-.038-.091-.085q-.042-.046-.076-.098t-.059-.11t-.039-.118q-.022.157-.022.321v6.917q0 .875.591 1.52l4 4.364q.398.434.909.61zm1.5 13.161V7.75h4.75q.063 0 .124-.01q.062-.011.121-.031q.059-.021.114-.05t.104-.069q.049-.038.091-.085q.042-.046.076-.098t.059-.11t.039-.118q.022.157.022.321v6.917q0 .875-.591 1.52l-4 4.364q-.398.434-.909.61");
}

</style>
