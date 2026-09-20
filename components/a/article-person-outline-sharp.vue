<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-ec95v0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:article-person-outline-sharp" /></template>
<style>
.i-ec95v0o {
  fill: currentColor;
  d: path("M5 19V5v4.187v-.571zm2.5-6.5h5.025q.03-.261.106-.512t.183-.488H7.5zm0 4h3.483q.251-.27.532-.486t.593-.358q-.024-.035-.04-.075q-.018-.04-.03-.081H7.5zM4 20V4h16v6.027q-.215-.265-.456-.467q-.24-.202-.544-.373V5H5v14h5.012q-.006.034-.009.07q-.003.034-.003.068V20zm11.475-5.59q-.59-.59-.59-1.41t.59-1.41t1.41-.59q.819 0 1.41.59q.59.59.59 1.41t-.59 1.41t-1.41.59t-1.41-.59M12.385 20v-.9q0-.465.235-.843q.236-.378.657-.546q.842-.355 1.747-.533t1.86-.178q.918 0 1.823.178t1.785.534q.422.167.657.545q.236.377.236.843v.9zM7.5 8.5h9v-1h-9z");
}

</style>
