<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbksmcibl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:algo" /></template>
<style>
.lbksmcibl {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.142 21l8.221-14.227l.99 3.683L9.268 21h3.115l3.953-6.844L18.181 21h2.792l-2.729-10.166L20.18 7.2h-2.836L16.138 3h-2.72L3.028 21z");
}

</style>
