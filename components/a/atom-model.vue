<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bigqk8bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:atom-model" /></template>
<style>
.bigqk8bdq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.28 4.72q1.53 1.529.197 4.8q-.356.873-.86 1.742q.066-.012.133-.012h.01q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-.067 0-.133-.012q.504.869.86 1.742q1.333 3.271-.197 4.8q-1.529 1.53-4.8.197q-1.244-.507-2.48-1.316q-1.236.809-2.48 1.316q-3.271 1.333-4.8-.197q-1.53-1.529-.197-4.8q.507-1.244 1.316-2.48q-.809-1.236-1.316-2.48q-1.333-3.271.197-4.8q1.529-1.53 4.8-.197q1.244.507 2.48 1.316q1.236-.809 2.48-1.316q3.271-1.333 4.8.197M12 9.75q-2.25 0-2.25 2.25T12 14.25T14.25 12T12 9.75");
}

</style>
