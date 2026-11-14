<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb_u6slrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chalk-ball" /></template>
<style>
.rb_u6slrc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.481 5.878Q11.214 5.75 12 5.75t1.519.128l.41-1.128h-3.858zm4.489.398q1.574.601 2.864 1.89Q20.25 10.583 20.25 14t-2.416 5.834T12 22.25t-5.834-2.416Q3.75 17.417 3.75 14t2.416-5.834q1.29-1.289 2.864-1.89l-.735-2.02q-.025-.069-.036-.142q-.012-.073-.008-.147q.003-.074.021-.145q.017-.072.048-.139q.032-.067.075-.127q.044-.059.098-.109t.118-.088t.133-.064Q8.868 3.25 9 3.25h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .132-.045.256z");
}

</style>
