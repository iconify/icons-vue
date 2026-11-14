<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwnq7ab-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-fig" /></template>
<style>
.zwnq7ab-s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 19.626q-1.501.511-3.129.436q-2.926-.136-3.589-2.346l-.01-.034q-.448-1.794.838-3.009l.012-.011q-.873-.334-1.591-.979q-1.749-1.567-1.528-4.001q.25-2.249 2.714-2.671q1.433-.246 2.678.301q.025-1.792.82-3.262Q9.708 1.75 12 1.75t3.535 2.3q.795 1.47.82 3.262q1.245-.547 2.678-.301q2.464.422 2.712 2.656q.223 2.449-1.526 4.016q-.718.645-1.591.979l.012.011q1.286 1.215.838 3.009l-.01.034q-.663 2.21-3.589 2.346q-1.628.075-3.129-.436V7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 6.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 7z");
}

</style>
