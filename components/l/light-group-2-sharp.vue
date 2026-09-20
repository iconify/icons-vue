<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rekznbcbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-group-2-sharp" /></template>
<style>
.rekznbcbt {
  fill: currentColor;
  d: path("m2.939 21l3.715-9.098V8.731H2.173L5.5 3h3.327l3.327 5.73h-4.5v3.172L11.358 21h-1.073l-2.637-6.396V21h-1v-6.396L4.012 21zm13.869-3.384q-1.221 0-2.104-.787t-1.098-2.002H11.5q0-1.316.663-2.459t1.766-1.922q.106-.987.762-1.72q.655-.734 1.636-.886V3h1v4.84q.956.152 1.621.886q.666.734.79 1.72q1.085.779 1.76 1.922t.675 2.459h-2.15q-.234 1.215-1.127 2.002q-.892.787-2.088.787m0-1.02q.756 0 1.33-.503q.575-.502.85-1.266H14.66q.236.764.802 1.266q.565.503 1.346.503");
}

</style>
