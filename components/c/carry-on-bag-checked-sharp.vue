<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uabjjrb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-checked-sharp" /></template>
<style>
.uabjjrb8c {
  fill: currentColor;
  d: path("m16.608 19.712l3.357-3.358l-.557-.558l-2.8 2.8l-1.4-1.4l-.558.558zm-2.136.816q-1.164-1.164-1.164-2.836q0-1.67 1.164-2.835t2.836-1.165q1.67 0 2.835 1.165t1.165 2.835q0 1.672-1.165 2.836q-1.164 1.164-2.835 1.164t-2.836-1.164M10.385 20V8H14V4h-1.616V3H15v9.166q-1.648.743-2.67 2.213q-1.022 1.469-1.022 3.275q0 .608.108 1.2q.107.594.361 1.146zM7 20V8h2.5v12z");
}

</style>
