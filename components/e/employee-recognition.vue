<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjsptuypg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:employee-recognition" /></template>
<style>
.cjsptuypg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.702 2.702Q1.75 3.654 1.75 5v10q0 3.25 3.25 3.25h.75V21q0 .125.041.243q.04.119.117.217q.045.059.101.107t.12.085q.064.036.135.06q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.053q.066-.033.124-.078l4.297-3.342H19q3.25 0 3.25-3.25V5q0-1.346-.952-2.298T19 1.75H5q-1.346 0-2.298.952m10.588 4.1v.001l.24.638q.174.464.669.486l.682.031q.953.044 1.248.951q.294.907-.451 1.502l-.534.426q-.387.309-.256.786l.182.657q.253.921-.518 1.481q-.772.561-1.569.036l-.57-.376q-.413-.272-.826 0l-.57.376q-.797.525-1.569-.036q-.771-.56-.518-1.48l.182-.659q.131-.476-.256-.785l-.534-.426q-.745-.595-.451-1.502q.295-.907 1.247-.951l.683-.031q.495-.022.669-.486l.24-.639q.335-.893 1.29-.893t1.29.893");
}

</style>
