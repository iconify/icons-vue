<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pia92gbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:commit-outline-rounded" /></template>
<style>
.pia92gbml {
  fill: currentColor;
  d: path("M9.015 15.363Q7.777 14.225 7.504 12.5H3.5q-.213 0-.357-.143T3 12t.143-.357t.357-.143h4.004q.273-1.725 1.51-2.863T12 7.5t2.995 1.138t1.501 2.862H20.5q.214 0 .357.143T21 12t-.143.357t-.357.143h-4.004q-.254 1.725-1.5 2.863Q13.747 16.5 12 16.5t-2.985-1.137M12 15.5q1.442 0 2.471-1.029T15.5 12t-1.029-2.471T12 8.5T9.529 9.529T8.5 12t1.029 2.471T12 15.5");
}

</style>
