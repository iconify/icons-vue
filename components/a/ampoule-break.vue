<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqx4q8n0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ampoule-break" /></template>
<style>
.uqx4q8n0n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.623 7.143l2.376-2.218q.359-.335.824-.49l1.19-.396q.903-.301 1.576.372t.373 1.575l-.398 1.191q-.154.465-.488.823l-2.219 2.377q-.651.698-1.606.714q-.954.016-1.629-.659l-.054-.054q-.675-.675-.659-1.629q.016-.955.714-1.606M6.376 6.084q-.126.189-.126.416v2q0 .209-.714.927Q3.75 11.226 3.75 13v5.5q0 2.75 2.75 2.75h4q2.75 0 2.75-2.75V13q0-1.774-1.786-3.573q-.714-.718-.714-.927v-2q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T10 5.75q-.227 0-.416.126L8.5 6.599l-1.084-.723q-.061-.041-.13-.069q-.068-.028-.14-.043t-.147-.014q-.074 0-.146.015q-.073.014-.141.042t-.129.07q-.062.041-.114.093q-.052.053-.093.114");
}

</style>
