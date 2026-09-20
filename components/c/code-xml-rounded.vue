<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz9zd6qre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:code-xml-rounded" /></template>
<style>
.sz9zd6qre {
  fill: currentColor;
  d: path("m3.114 12l3.24 3.24q.14.147.143.348t-.143.347T6 16.08t-.354-.147l-3.369-3.368q-.242-.243-.242-.566t.242-.565l3.37-3.37Q5.791 7.92 6 7.92t.354.147q.146.145.146.346t-.146.347zm6.25 7.263q-.1-.19-.033-.379l4.4-14.08q.067-.189.247-.29t.368-.033t.3.247t.042.368l-4.419 14.1q-.067.188-.247.29q-.18.1-.368.033t-.29-.256M20.888 12l-3.24-3.24q-.147-.146-.147-.348t.146-.347T18 7.92t.354.147l3.369 3.368q.243.243.243.566t-.243.566l-3.37 3.368q-.145.147-.353.147t-.354-.147t-.146-.346t.146-.347z");
}

</style>
