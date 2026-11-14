<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fldizbeaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-branches" /></template>
<style>
.fldizbeaq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.829 4.256q-5.788.102-8.079 1.996V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q6.074 1.75 6 1.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v12.799q-2.5.351-2.5 3.201q0 3.25 3.25 3.25t3.25-3.25q0-2.85-2.5-3.201v-2.86q2.291 1.713 8.079 1.806q.195.877.872 1.554q.952.953 2.299.953t2.299-.953t.951-2.3q.001-1.345-.951-2.298T18 10.248t-2.299.953q-.673.674-.87 1.544Q6.75 12.623 6.75 9.5q0-3.604 8.081-3.744q.197.87.87 1.543q.952.953 2.299.953t2.299-.953t.951-2.3q.001-1.345-.951-2.298T18 1.748t-2.299.953q-.677.678-.872 1.555");
}

</style>
