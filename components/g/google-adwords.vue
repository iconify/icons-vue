<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o8osx0bbn"/><path class="dozkazbia"/><path class="ulzj_7blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-adwords" /></template>
<style>
.dozkazbia {
  d: path("M193.668 255.833l62.332.01l-.063-.146L170.816.271v245.822c5.784 5.982 13.853 9.74 22.852 9.74");
  fill: var(--svg-color--13a564, #13A564);
}

.o8osx0bbn {
  d: path("M127.995 127.87l35.577 106.771c.01.021.01.042.02.074c1.556 4.321 4.061 8.163 7.193 11.389l3.937-8.204l-2.351-230.09l-1.586-7.518l-.094-.25l-3.285 2.804l-40.739 121.968l1.328 3.056");
  fill: var(--svg-color--097243, #097243);
}

.ulzj_7blf {
  d: path("M85.319.031l-.01.094l-.031-.094L.063 255.708l-.063.135h62.332c8.989 0 17.068-3.758 22.852-9.76c3.131-3.236 5.637-7.067 7.192-11.389c.011-.032.011-.053.021-.063L170.712 0H85.309v.031h.01");
  fill: var(--svg-color--4d7bbe, #4D7BBE);
}

</style>
