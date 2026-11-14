<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud7u53y9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:astrophotography" /></template>
<style>
.ud7u53y9k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 7.055Q1.75 7.861 1.75 9v9q0 2.75 2.75 2.75h15q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-2.575l-1.282-2.136q-.05-.083-.119-.151q-.07-.068-.154-.116q-.085-.048-.179-.072q-.094-.025-.191-.025H9q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151L7.075 6.25H4.5q-1.139 0-1.945.805m10.656 3.459l.164.411q.175.441.648.472l.442.029q.881.059 1.154.898q.273.838-.404 1.404l-.341.283q-.366.304-.249.764l.109.426q.218.859-.496 1.378t-1.461.049l-.375-.236q-.402-.254-.803-.001l-.376.237q-.747.47-1.461-.049t-.497-1.375l.111-.431q.116-.458-.249-.761l-.341-.284q-.678-.566-.405-1.404q.273-.839 1.153-.898l.442-.029q.474-.031.649-.471l.164-.412q.33-.819 1.211-.819t1.21.817z");
}

</style>
