<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(2 2)scale(.11667)" class="kuf42lb8e"><rect class="fbh4whsvy"/><path class="abk2hw08c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-affinity" /></template>
<style>
.abk2hw08c {
  fill-rule: nonzero;
  d: path("M112.91 165.98c-10.413 0-17.037-6.317-17.037-14.329c0-34.287 90.164-41.151 90.164-77.563c0-22.213-25.731-31.787-58.577-31.787c-19.98 0-42.571 3.698-63.552 10.315v43.438c30.919-22.52 65.272-32.16 87.4-32.16c13.914 0 23.355 3.882 23.355 10.838c0 28.658-124.35 24.117-124.35 86.042c0 23.736 16.321 37.335 39.283 37.335c34.732 0 61.003-33.753 80.657-74.897l3.982 1.43c-10.351 25.143-31.771 52.712-35.943 70.434h44.715v-91.685H172.68c-14.99 32.574-36.957 62.59-59.767 62.59");
}

.fbh4whsvy {
  width: 240px;
  height: 240px;
  fill: var(--svg-color--a7f175, #a7f175);
  ry: 40px;
}

.kuf42lb8e {
  fill-rule: evenodd;
  stroke-linejoin: round;
  stroke-miterlimit: 2;
}

</style>
