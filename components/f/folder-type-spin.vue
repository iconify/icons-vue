<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gyhhq72wf"/><path class="vty-gzbdq"/><path class="sa0rmn_cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-spin" /></template>
<style>
.gyhhq72wf {
  fill: var(--svg-color--999, #999);
  d: path("M27.35 5.542h-9.227l-2.083 4.2H4.433v16.8h25v-21zm0 4.2h-8.135l1.091-2.1h7.044z");
}

.sa0rmn_cz {
  d: path("M23.813 15.81a6.738 6.774 0 0 0-6.739 6.775a6.738 6.774 0 0 0 6.739 6.774a6.738 6.774 0 0 0 6.738-6.774a6.738 6.774 0 0 0-6.738-6.775m.02 1.628a5.14 5.168 0 0 1 5.141 5.167a5.14 5.168 0 0 1-5.14 5.168a5.14 5.168 0 0 1-5.14-5.169a5.14 5.168 0 0 1 5.14-5.166");
}

.vty-gzbdq {
  d: path("M20.91 14.457h1.687v16.297H20.91z");
}

</style>
