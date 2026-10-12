<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ika4c08uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-spectrum-sharp" /></template>
<style>
.ika4c08uy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.5c.08-.13.33-.52.5-.8c.17-.27.33-.55.5-.83s.33-.57.5-.84c.17-.28.33-.55.5-.81c.17-.25.33-.5.5-.71c.17-.22.33-.42.5-.57l.306-.27l.194-.08l.286-.118l.214.038l.265.047l.235.193l.233.192l.267.408c.17.26.33.58.5.95s.33.81.5 1.27s.33.98.5 1.5c.17.51.33 1.08.5 1.6s.33 1.06.5 1.53s.33.93.5 1.27l.302.622l.198.198l.271.271l.229-.081l.243-.071l.257-.439c.17-.29.33-.72.5-1.22s.33-1.14.5-1.78c.17-.65.33-1.4.5-2.09s.33-1.43.5-2.03s.33-1.19.5-1.58l.293-.655l.207-.085l.249-.117l.251.427l.2.33l.3 1.04c.17.6.33 1.41.5 2.2s.33 1.73.5 2.52s.33 1.63.5 2.2l.301 1.028l.199.222l.253.267l.247-.407l.195-.333l.305-1.237c.17-.7.33-1.7.5-2.6c.17-.91.33-2.01.5-2.84c.17-.82.33-1.66.5-2.11s.42-.49.5-.59M2.75 19.5h18.5");
}

</style>
