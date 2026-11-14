<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq6uzebhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bootcamp" /></template>
<style>
.oq6uzebhu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.719 10.268Q7.149 9.25 9 9.25h3.575q1.408-2.451.617-4.19q-.823-1.81-3.692-1.81q-3.09 0-4.147 2.034q-1.022 1.965.366 4.984m8.549-1.018H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.794q-.228 1.903-1.64 3.316Q11.382 20.75 9 20.75t-4.066-1.684T3.25 15q0-2.106 1.317-3.667q-1.985-3.972-.545-6.742Q5.5 1.75 9.5 1.75q3.835 0 5.058 2.69q.974 2.143-.29 4.81");
}

</style>
