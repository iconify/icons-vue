<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1gu_ti_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:article-person-sharp" /></template>
<style>
.u1gu_ti_x {
  fill: currentColor;
  d: path("M7.5 8.5h9v-1h-9zM4 20V4h16v6.027q-.594-.663-1.4-1.037t-1.716-.374q-1.374 0-2.484.794t-1.586 2.09H7.5v1h5.025q-.089.673.058 1.327q.146.654.475 1.25q-.25.096-.49.192q-.241.097-.472.231H7.5v1h3.483q-.495.53-.739 1.222T10 19.139V20zm8.385 0v-.9q0-.465.235-.843q.236-.378.657-.546q.842-.355 1.747-.533t1.86-.178q.918 0 1.823.178t1.785.534q.422.167.657.545q.236.377.236.843v.9zm3.09-5.59q-.59-.59-.59-1.41t.59-1.41t1.41-.59q.819 0 1.41.59q.59.59.59 1.41t-.59 1.41t-1.41.59t-1.41-.59");
}

</style>
