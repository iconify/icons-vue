<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr6bvxwcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-rolling" /></template>
<style>
.mr6bvxwcr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.995 3.495Q1.75 4.74 1.75 6.5t1.245 3.005q.456.456.981.745q-.525.289-.981.745Q1.75 12.24 1.75 14v2.5q0 1.76 1.245 3.005T6 20.75h6q1.76 0 3.005-1.245q.677-.676.986-1.505q.141.076.298.141l2.5 1.041q1.234.515 2.348-.227t1.113-2.08v-3.75q0-1.338-1.113-2.08q-1.114-.742-2.348-.227l-2.5 1.041q-.258.107-.472.243q-.302-.597-.812-1.107q-.27-.271-.565-.483q.864-.306 1.565-1.007Q17.25 8.26 17.25 6.5t-1.245-3.005T13 2.25T9.995 3.495q-.279.278-.495.583q-.216-.305-.495-.583Q7.76 2.25 6 2.25T2.995 3.495M9.5 8.922q.216.305.495.583q.129.129.264.245H8.741q.135-.116.264-.245q.279-.278.495-.583");
}

</style>
