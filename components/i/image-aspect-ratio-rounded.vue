<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvbe3obtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-aspect-ratio-rounded" /></template>
<style>
.pvbe3obtt {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm2.962-7.233q.23-.233.23-.578t-.233-.574q-.234-.23-.578-.23q-.345 0-.575.233t-.23.578t.234.574t.577.23t.575-.233m3.808 0q.23-.233.23-.578t-.234-.575t-.578-.23t-.574.234t-.23.578t.233.574t.578.23t.575-.233m3.807 0q.23-.233.23-.578t-.233-.575t-.578-.23t-.574.234t-.23.578t.233.574t.578.23t.574-.233m0 3.807q.23-.233.23-.577q0-.345-.233-.575t-.578-.23t-.574.233t-.23.578t.233.575t.578.23t.574-.234");
}

</style>
