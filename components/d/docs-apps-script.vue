<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4y6mebts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:docs-apps-script" /></template>
<style>
.y4y6mebts {
  fill: currentColor;
  d: path("M13 21q-.425 0-.712-.288T12 20t.288-.712T13 19h2.825l-2.3-1.625q-.35-.25-.413-.638t.163-.737t.625-.413t.75.163l2.325 1.6L16 14.7q-.15-.4.025-.762t.575-.513t.775.025t.525.575l.95 2.65l.75-2.725q.125-.4.462-.612t.738-.088t.625.463t.1.737l-1.55 5.8q-.1.35-.363.55T19 21zM3 18v-2h7.075q-.075.525-.062 1t.087 1zm0-4v-2h9.65q-.575.4-1.037.9T10.8 14zm0-4V8h15v2zm0-4V4h15v2z");
}

</style>
