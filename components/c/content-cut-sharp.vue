<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr4ca9eod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-cut-sharp" /></template>
<style>
.hr4ca9eod {
  fill: currentColor;
  d: path("m19.385 20.539l-7.308-7.308l-3.12 3.119q.22.375.324.79t.104.86q0 1.362-.973 2.335q-.974.973-2.335.973t-2.335-.973Q2.77 19.362 2.77 18t.973-2.334t2.335-.974q.444 0 .86.104q.415.104.79.323L10.847 12l-3.12-3.12q-.375.22-.79.324t-.86.104q-1.362 0-2.335-.973Q2.77 7.36 2.77 6t.973-2.334t2.335-.974t2.335.973q.972.974.972 2.335q0 .444-.103.86q-.104.415-.323.79L21.23 19.923v.616zm-4.77-9.847l-1.23-1.23l6-6h1.846v.615zM7.712 7.634Q8.385 6.96 8.385 6T7.71 4.366t-1.634-.674t-1.634.674Q3.77 5.041 3.77 6t.674 1.634t1.634.674t1.634-.674m4.37 4.37q-.004.004-.004-.004t.004-.004t-.004.004t-.004-.004t.004.004t-.004.004t.004-.004t.004.004m-4.37 7.63q.673-.675.673-1.634t-.674-1.634q-.674-.674-1.633-.674q-.96 0-1.634.674q-.674.675-.674 1.634t.674 1.634q.674.674 1.634.674t1.633-.674");
}

</style>
