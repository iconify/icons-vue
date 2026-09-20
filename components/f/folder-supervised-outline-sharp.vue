<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f80eh5b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-supervised-outline-sharp" /></template>
<style>
.f80eh5b9s {
  fill: currentColor;
  d: path("M4 18V6v4.435V10zm-1 1V5h6.596l2 2H21v3.91q-.238-.152-.479-.265q-.24-.112-.521-.21V8h-8.806l-2-2H4v12h7.364q.055.275.131.516q.076.24.186.484zm11.385 0v-.165q0-.876.869-1.355t2.438-.48t2.439.48t.869 1.355V19zm2.241-4.049q-.434-.434-.434-1.066t.434-1.067t1.066-.433t1.067.433t.433 1.067t-.433 1.066t-1.067.434t-1.066-.434");
}

</style>
