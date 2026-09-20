<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhzq5cjqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:how-to-reg-rounded" /></template>
<style>
.vhzq5cjqi {
  fill: currentColor;
  d: path("M7.82 10.508q-.878-.877-.878-2.123t.877-2.123t2.123-.877t2.124.877t.876 2.123t-.876 2.123t-2.124.877t-2.123-.877m-3.838 8.108q-.44 0-.74-.3q-.299-.299-.299-.739v-.608q0-.767.377-1.232q.377-.466.954-.764q1.275-.65 2.51-1.004q1.234-.353 3.16-.353h.556q.265 0 .493.03q.404.031.535.41t-.161.671l-.772.771q-.448.448-.557 1.046t.234 1.089q.223.32.068.652q-.154.33-.539.33zm11.319-.324l4.696-4.696q.14-.14.345-.15q.203-.01.363.15t.16.354t-.16.354l-4.838 4.838q-.243.243-.566.243t-.565-.243l-1.839-1.838q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16z");
}

</style>
