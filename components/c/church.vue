<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb8bn2bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:church" /></template>
<style>
.eb8bn2bkz {
  fill: currentColor;
  d: path("M2.5 21.5v-7.27l4-1.774V9.154l5-2.52V4.347h-2v-1h2v-2h1v2h2v1h-2v2.289l5 2.519v3.302l4 1.775V21.5h-7.77v-3.346q0-.714-.507-1.223t-1.22-.508t-1.223.509t-.51 1.222V21.5zm10.293-8.711q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.79.326q-.321.327-.321.793q0 .467.326.79q.327.322.793.322q.467 0 .79-.327");
}

</style>
