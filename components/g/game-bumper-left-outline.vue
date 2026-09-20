<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg3cznbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-bumper-left-outline" /></template>
<style>
.tg3cznbns {
  fill: currentColor;
  d: path("M21 5v10.73q0 1.368-.973 2.329q-.973.96-2.354.96H6.327q-1.406 0-2.366-.96Q3 17.098 3 15.73V5zm-1 1H4v9.73q0 .947.671 1.618t1.656.671h11.346q.96 0 1.643-.671q.684-.671.684-1.617zm0 0H4zm-7.454 9.116l2.254.005q.992 0 1.587-.474q.594-.474.594-1.308q0-.63-.35-.978t-1.012-.486v-.044q.564-.117.848-.482t.285-.945q0-.82-.58-1.16q-.581-.34-1.716-.34h-1.91zm.856-3.6V9.683h1.033q.742 0 1.098.207t.356.706q0 .494-.347.713q-.346.218-1.03.207zm0 2.82v-2.07h1.246q.693 0 1.066.262t.373.782q0 .494-.355.76t-1.028.266zm-6.279.78h3.796v-.827H7.98V8.904h-.856z");
}

</style>
