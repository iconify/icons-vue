<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8wv_m6hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-wifi-4-bar" /></template>
<style>
.n8wv_m6hk {
  fill: currentColor;
  d: path("m7.566 15.41l-1.058-1.064q1.16-.969 2.573-1.475T12 12.366t2.92.505t2.572 1.475l-1.058 1.064q-.95-.76-2.083-1.152T12 13.866t-2.351.392t-2.084 1.152m-5.47-5.233L1.011 9.133Q3.302 7.11 6.13 6.055T12 5t5.87 1.045q2.828 1.046 5.118 3.088l-1.082 1.044q-2.05-1.802-4.598-2.749T12 6.481t-5.308.947t-4.598 2.749m2.748 2.62l-1.057-1.045Q5.5 10.246 7.619 9.469t4.406-.777t4.393.765t3.823 2.27l-1.058 1.064q-1.5-1.291-3.345-1.955t-3.819-.663q-1.978 0-3.828.666q-1.849.667-3.349 1.957m6.073 5.809q-.453-.453-.453-1.086t.453-1.076T12 16t1.086.443q.452.443.452 1.076t-.453 1.086t-1.085.453t-1.086-.453");
}

</style>
