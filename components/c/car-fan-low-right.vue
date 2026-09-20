<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7w10vbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-low-right" /></template>
<style>
.g7w10vbth {
  fill: currentColor;
  d: path("m9.802 22l-.86-.52l3.239-5.076q.198-.321.497-.488t.637-.166h3.627l1.623-5.64q.193-.645.637-1.031q.444-.387 1.006-.387q.776 0 1.28.595t.354 1.372L20.691 16.4q-.125.566-.563.929t-1.009.363h-6.321zM20.519 7.692q-.613 0-1.037-.424t-.424-1.037t.424-1.038t1.037-.424t1.038.424t.424 1.038t-.424 1.037t-1.038.424M7.116 11.385L3 7.269l.688-.694l2.927 2.87V3h1v6.444l2.927-2.863l.708.688z");
}

</style>
