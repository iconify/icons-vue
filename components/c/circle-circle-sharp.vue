<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcphkzb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:circle-circle-sharp" /></template>
<style>
.hcphkzb0h {
  fill: currentColor;
  d: path("M8.494 20.299q-1.642-.701-2.867-1.926t-1.926-2.866T3 12.003t.701-3.508t1.926-2.857T8.493 3.71T11.998 3t3.509.709t2.859 1.922t1.925 2.857t.709 3.509t-.71 3.509t-1.926 2.867t-2.856 1.926t-3.506.701t-3.508-.701m3.504-5.01q-1.363 0-2.325-.959q-.961-.958-.961-2.327t.958-2.32t2.327-.952t2.32.954t.952 2.317t-.954 2.325t-2.317.961m3.03-.25q1.241-1.252 1.241-3.038t-1.241-3.028Q13.787 7.731 12 7.731T8.963 8.972T7.712 12t1.25 3.038T12 16.288t3.028-1.25");
}

</style>
