<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr7pc3pzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-lantern" /></template>
<style>
.wr7pc3pzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 5q0-2.25 2.25-2.25T14.25 5q0 .413-.076.75h.3q.79 0 1.406.493l.838.671q.725.583.418 1.459q-.082.233-.208.404q.322.576.322 1.473v6.5q0 1.036-.732 1.768q-.068.067-.138.128q.112.16.206.348l.086.172q.358.717-.064 1.401q-.423.683-1.226.683H8.618q-.803 0-1.226-.683q-.422-.684-.063-1.402l.084-.17q.095-.188.207-.349q-.07-.061-.138-.128q-.732-.732-.732-1.768v-6.5q0-.898.322-1.473q-.126-.171-.208-.404q-.307-.876.416-1.458l.841-.672q.615-.493 1.405-.493h.3Q9.75 5.413 9.75 5M12 16.5q2.265 0 2.343-2.034q.064-1.663-1.786-3.718q-.026-.029-.055-.055q-.111-.1-.252-.15q-.14-.05-.289-.042t-.284.072t-.234.175q-1.85 2.055-1.786 3.718Q9.735 16.5 12 16.5");
}

</style>
