<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w2i6iwrjp"/><path class="vty-gzbdq"/><path class="sa0rmn_cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-spin-opened" /></template>
<style>
.sa0rmn_cz {
  d: path("M23.813 15.81a6.738 6.774 0 0 0-6.739 6.775a6.738 6.774 0 0 0 6.739 6.774a6.738 6.774 0 0 0 6.738-6.774a6.738 6.774 0 0 0-6.738-6.775m.02 1.628a5.14 5.168 0 0 1 5.141 5.167a5.14 5.168 0 0 1-5.14 5.168a5.14 5.168 0 0 1-5.14-5.169a5.14 5.168 0 0 1 5.14-5.166");
}

.vty-gzbdq {
  d: path("M20.91 14.457h1.687v16.297H20.91z");
}

.w2i6iwrjp {
  fill: var(--svg-color--b3b3b3, #b3b3b3);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21zm-7.2 2.1h7.1v2.1h-8.1zm5.5 6.1H6.6v-1.9h20.8v7.626z");
}

</style>
