<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b316_2bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:junction-number" /></template>
<style>
.b316_2bdh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.005 4.195l4.8 4.8Q21.05 10.239 21.05 12t-1.245 3.005l-4.8 4.8Q13.761 21.05 12 21.05t-3.005-1.245l-4.8-4.8Q2.95 13.761 2.95 12t1.245-3.005l4.8-4.8Q10.239 2.95 12 2.95t3.005 1.245M11.424 8.52l-1.25 1.5q-.047.057-.083.121q-.035.065-.057.136q-.022.07-.03.144t-.001.147t.028.144t.055.137q.034.065.081.122q.046.058.103.105q.051.043.11.076q.058.033.121.055q.063.023.129.033t.133.01t.133-.014t.128-.038t.119-.059t.107-.08V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9q0-.167-.071-.318t-.199-.258q-.101-.084-.225-.129q-.123-.045-.255-.045q-.167 0-.318.071t-.258.199");
}

</style>
