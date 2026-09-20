<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3udr2b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-recline-extra" /></template>
<style>
.l3udr2b1g {
  fill: currentColor;
  d: path("M7.885 6.577q-.69 0-1.192-.501t-.5-1.191t.5-1.192t1.192-.5t1.191.5t.501 1.191t-.501 1.192t-1.191.501M14 19H8.05q-.69 0-1.243-.443t-.69-1.134L4.04 7h1.01l2.085 10.385q.057.23.279.423q.22.192.452.192H14zm5.077 2.385L16.523 17h-7.22q-.551 0-.935-.332t-.514-.845l-1.177-5.62q-.217-1.026.466-1.75q.684-.722 1.595-.722q.702 0 1.29.419t.749 1.146L11.992 15h3.712q.39 0 .725.198t.552.571l2.961 5.116z");
}

</style>
