<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8upb0u9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:claim-direct-pay" /></template>
<style>
.b8upb0u9s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.25V8q0-2.25 2.25-2.25h1.099l1.777-2.666q.051-.077.12-.139q.068-.063.15-.106q.082-.044.172-.066T7.5 2.75h6q.167 0 .318.071t.258.199l2.275 2.73H19.5q2.25 0 2.25 2.25v3.25q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T21 12h-8.127q.127.436.127 1q0 2.5-2.5 2.5T8 13q0-.564.127-1H6.8q.2.459.2 1q0 1.036-.732 1.768T4.5 15.5Q2 15.5 2 13q0-.619.153-1.085q-.091-.047-.166-.118t-.128-.158t-.081-.187t-.028-.202m18.5 2h-3.5q-2.5 0-2.5 2.5v3q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-3q0-1.036-.732-1.768t-1.768-.732m-4.5 2.5q0-1 1-1h3.5q1 0 1 1v3q0 .414-.293.707t-.707.293h-3.5q-1 0-1-1zm.75 1.5q0-2 2-2t2 2t-2 2t-2-2m1.5 0q0 .5.5.5t.5-.5t-.5-.5t-.5.5");
}

</style>
