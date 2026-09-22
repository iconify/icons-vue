<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmx6rbc4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:import-spark-outline" /></template>
<style>
.cmx6rbc4r {
  fill: currentColor;
  d: path("M4 8.73V5.617q0-.691.463-1.153T5.616 4h6.307v1H5.616q-.231 0-.424.192T5 5.616V8.73zm6.846 6.693l-.707-.72l2.203-2.203H4v-1h8.342l-2.204-2.204l.708-.719L14.27 12zM5.616 20q-.691 0-1.153-.462T4 18.384V15.27h1v3.115q0 .231.192.424t.423.192h12.77q.23 0 .423-.192t.192-.424v-6.307h1v6.307q0 .691-.462 1.153T18.384 20zM18.404 9.692q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.362 2.387-1.359t1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.362 1.39 1.359 2.387t2.387 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.997.997-1.36 2.387q-.024.15-.2.15");
}

</style>
