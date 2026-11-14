<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtlfxbctm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:design-token-colour" /></template>
<style>
.xtlfxbctm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.25q4.339 0 7.322 2.762Q22.25 7.723 22.25 11.5q0 2.508-1.844 3.693q-1.603 1.031-3.588.535q-1.093-.274-1.632.333q-.523.588-.015 1.604q.95 1.9-.266 3.115q-.969.97-2.905.97q-4.389 0-7.333-2.835Q1.75 16.106 1.75 12t2.917-6.915Q7.611 2.25 12 2.25M12.25 8q0 2.25 2.25 2.25T16.75 8T14.5 5.75T12.25 8m-1.46.168l-.665-.384v-.001Q9 7.134 7.875 7.784l-.665.383q-1.125.65-1.125 1.949v.768q0 1.299 1.125 1.948l.665.385q1.125.649 2.25-.001l.665-.383q1.125-.65 1.125-1.949v-.768q0-1.299-1.125-1.948");
}

</style>
