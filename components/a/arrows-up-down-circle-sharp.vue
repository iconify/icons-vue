<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3q01patb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-up-down-circle-sharp" /></template>
<style>
.f3q01patb {
  fill: currentColor;
  d: path("m12 17.52l3.173-3.155l-.707-.688l-1.966 1.946V8.396l1.966 1.946l.707-.708L12 6.5L8.846 9.635l.708.707L11.5 8.396v7.227l-1.946-1.946l-.708.689zm-3.506 2.779q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701");
}

</style>
