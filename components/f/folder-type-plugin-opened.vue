<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wbthw2byq"/><path class="jmw_wsa_y"/><path class="j6_wo0b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-plugin-opened" /></template>
<style>
.j6_wo0b4w {
  fill: var(--svg-color--e76a00, #e76a00);
  d: path("M20 12.5V14h-4a2.006 2.006 0 0 0-2 2v4h-1.5a2.5 2.5 0 0 0 0 5H14v4a2.006 2.006 0 0 0 2 2h3.8v-1.5a2.7 2.7 0 0 1 5.4 0V31H29a2.006 2.006 0 0 0 2-2v-3.8h-1.5a2.7 2.7 0 0 1 0-5.4H31V16a2.006 2.006 0 0 0-2-2h-4v-1.5a2.5 2.5 0 0 0-5 0");
}

.jmw_wsa_y {
  fill: var(--svg-color--ffd69b, #ffd69b);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.wbthw2byq {
  fill: var(--svg-color--ffd69b, #ffd69b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

</style>
