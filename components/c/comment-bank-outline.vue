<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc6nosbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comment-bank-outline" /></template>
<style>
.bc6nosbhb {
  fill: currentColor;
  d: path("M13.385 10.116V4h-8.77q-.23 0-.423.192T4 4.615v13.03L5.65 16h13.735q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T19.385 4h-2v6.116l-2-1.193zM3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v10.769q0 .69-.463 1.153T19.385 17H6.077zM4 4v13.385z");
}

</style>
