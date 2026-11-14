<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opbmx-bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:job-offer" /></template>
<style>
.opbmx-bdp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.875 4.25H5.125q-2.853 0-3.294 2.411q.021-.042.048-.082q.042-.061.094-.113q.053-.052.115-.093q.062-.04.13-.068t.141-.042t.146-.013t.147.015q.072.015.14.044t.129.07l6.376 4.327Q10.171 9.75 12 9.75t2.703.956l6.376-4.327q.123-.083.269-.114q.147-.03.293-.002q.147.028.271.11t.209.206q.027.04.048.082q-.441-2.411-3.294-2.411m-3.498 7.811q.123.533.123 1.189q0 3.5-3.5 3.5t-3.5-3.5q0-.656.123-1.189l-6.544-4.44q-.119-.081-.2-.201q-.081-.119-.112-.26q-.017.224-.017.465v8.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-8.75q0-.241-.017-.465q-.031.141-.112.26t-.2.201z");
}

</style>
