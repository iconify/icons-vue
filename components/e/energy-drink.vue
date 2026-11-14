<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="expln_lsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:energy-drink" /></template>
<style>
.expln_lsp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75H8q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151l-1.5 2.5Q5.75 4.792 5.75 5v14.5q0 2.75 2.75 2.75h7q2.75 0 2.75-2.75V5q0-.208-.107-.386l-1.5-2.5q-.05-.083-.119-.151q-.07-.068-.154-.116q-.085-.048-.179-.072q-.094-.025-.191-.025m-4.818 7.54l.001-.003q.527-.756 1.355-.35q.83.407.553 1.287l-.215.687q-.039.126.039.233q.078.106.21.106q.892-.001 1.349.766q.458.766.034 1.551l-1.513 2.809q-.471.865-1.393.519t-.708-1.311l.32-1.409q.037-.163-.068-.294q-.104-.131-.272-.131q-.888-.001-1.298-.789t.098-1.517z");
}

</style>
