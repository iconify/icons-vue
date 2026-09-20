<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nor5ryb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:in-home-mode-outline-rounded" /></template>
<style>
.nor5ryb0q {
  fill: currentColor;
  d: path("M6.616 19q-.672 0-1.144-.472T5 17.385V9.452l-2 1.486q-.171.116-.363.095q-.19-.022-.325-.199q-.135-.17-.111-.359t.195-.323l8.629-6.438q.217-.162.463-.233T12 3.409q.248 0 .503.072q.255.071.472.232l8.648 6.433q.171.135.195.323t-.11.366q-.135.176-.323.195q-.189.018-.366-.097l-8.653-6.414q-.154-.115-.366-.115t-.365.115L6 8.716v8.669q0 .269.173.442t.443.173h1.563q.213 0 .354.143t.14.357t-.143.357t-.357.143zm7.723 1.606q-.137-.047-.268-.177l-2.613-2.613q-.146-.147-.146-.345t.146-.363t.354-.156t.354.156l2.47 2.465l5.316-5.296q.146-.146.347-.143t.347.149t.146.354t-.146.354l-5.444 5.438q-.13.13-.267.177t-.298.046t-.298-.046");
}

</style>
