<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-nz5nvpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-check-2-outline-sharp" /></template>
<style>
.j-nz5nvpf {
  fill: currentColor;
  d: path("M4 18V6v5.935v-.627zm-1 1V5h6.596l2 2H21v5.487q-.238-.172-.479-.303q-.24-.132-.521-.25V8h-8.806l-2-2H4v12h6.942q.02.256.037.506t.09.494zm13.602.712l3.34-3.335l-.626-.627l-2.714 2.702L15.3 17.15l-.627.633zm3.541-4.855q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165");
}

</style>
