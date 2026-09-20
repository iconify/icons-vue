<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za1qhvbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:2d-2-outline" /></template>
<style>
.za1qhvbvn {
  fill: currentColor;
  d: path("M5.483 16.217v-.969q.967-.736 1.722-1.408q.755-.673 1.287-1.328q.427-.539.71-1.153q.283-.615.283-1.293q0-.777-.413-1.206q-.412-.43-1.133-.43q-.697 0-1.11.446q-.413.445-.481 1.159l-.917-.106q.054-1.023.734-1.716t1.793-.694q1.19 0 1.841.656t.651 1.798q0 .868-.34 1.629q-.34.762-.89 1.429q-.518.66-1.173 1.224t-1.264 1.037l.011.018h3.733v.907zm6.66-.005V7.706h2.85q1.886 0 2.875 1.156t.99 3.1t-.993 3.097t-2.873 1.153zm.976-.954h1.85q1.458 0 2.188-.89q.73-.891.73-2.406t-.73-2.409t-2.188-.893h-1.85z");
}

</style>
