<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pbmnkkb0i"/><path class="xzhj196ty"/><path class="zknejxbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-dapr-opened" /></template>
<style>
.pbmnkkb0i {
  fill: var(--svg-color--7b8bdb, #7b8bdb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.xzhj196ty {
  fill: var(--svg-color--0d2192, #0d2192);
  d: path("M30.53 28.808h-3.457v-8.29a.253.253 0 0 0-.252-.253H14.35a.253.253 0 0 0-.252.253v8.29H10.47a.47.47 0 0 0-.47.47v1.252a.47.47 0 0 0 .47.47h20.06a.47.47 0 0 0 .47-.47v-1.252a.47.47 0 0 0-.47-.47");
}

.zknejxbep {
  fill: var(--svg-color--20329b, #20329b);
  d: path("M10.47 31h6.03v-1.6h2.4v-9.135h-4.55a.253.253 0 0 0-.252.253v8.29H10.47a.47.47 0 0 0-.47.47v1.252a.47.47 0 0 0 .47.47");
}

</style>
