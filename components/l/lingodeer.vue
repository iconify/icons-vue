<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="pr52f_b5y"><path class="jvy0-dhhb"/><path class="o0tukhbuy"/><path class="e4zco5b6k"/><path class="le3v-fywf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lingodeer" /></template>
<style>
.e4zco5b6k {
  stroke-miterlimit: 15.118;
  d: path("M38.36 8.156c-.571 1.833-1.918 4.512-3.908 4.64M9.64 8.157c.571 1.833 1.918 4.512 3.908 4.64");
}

.jvy0-dhhb {
  stroke-linejoin: round;
  d: path("m12.434 15.892l2.01 24.96h19.113l2.008-24.96z");
}

.le3v-fywf {
  stroke-linejoin: round;
  d: path("m37.211 15.892l5.289-1.933l-1.298 3.69zm-26.422 0l-5.29-1.933l1.3 3.69zm18.424 6.895c.486 0 .877.39.877.876v3.442c0 .485-.391.876-.877.876s-.876-.39-.876-.876v-3.442c0-.486.39-.876.876-.876m-10.426 0a.875.875 0 0 0-.877.876v3.442c0 .485.391.876.877.876s.876-.39.876-.876v-3.442a.875.875 0 0 0-.876-.876m3.987 2.303q1.226-.585 2.452 0");
}

.o0tukhbuy {
  stroke-linejoin: round;
  d: path("M22.629 25.139a6.347 6.347 0 1 1-12.694 0a6.347 6.347 0 0 1 12.694 0m2.742 0a6.347 6.347 0 1 0 12.694 0a6.347 6.347 0 0 0-12.694 0m-3.094 11.426h3.446l-1.718 1.705zm13.92-29.417c-.424 3.53-1.639 6.605-4.672 8.636M11.803 7.148c.424 3.53 1.639 6.605 4.672 8.636");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

</style>
