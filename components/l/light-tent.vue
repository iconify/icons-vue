<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3jv3lq8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:light-tent" /></template>
<style>
.l3jv3lq8c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.97 2.47l-4.5 4.5q-.106.105-.163.243T2.25 7.5v13q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h13l.036-.001q.14-.007.268-.063q.127-.057.226-.156l4.5-4.5q.106-.105.163-.243T21.25 16V3q0-.034-.003-.067q-.012-.132-.068-.251t-.149-.212q-.105-.106-.243-.163T20.5 2.25h-13q-.149 0-.287.057t-.243.163m11.719 1.28l-3 3H4.811l3-3zM16.75 7.811l3-3v10.878l-3 3zm-1.5 11.939H3.75V8.25h11.5zm-9-4.75q0-3.25 3.25-3.25T12.75 15T9.5 18.25T6.25 15");
}

</style>
