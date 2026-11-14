<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcnvx32yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bride" /></template>
<style>
.mcnvx32yv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.191 2.835q-.264.113-.526.244q-.129.064-.225.172q-.095.107-.145.242q-.078.072-.154.148Q5.75 5.032 5.75 7t1.391 3.359T10.5 11.75t3.359-1.391T15.25 7q0-1.473-.78-2.623q2.422 1.17 3.318 3.86l2.159 6.909l-3.873-.369Q13.808 13.25 10.5 13.25q-3.462 0-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h13q1.75 0 1.75-1.75q0-1.716-.928-3.049l3.107.296q.15.014.295-.031q.07-.022.135-.058q.065-.035.122-.082q.056-.048.103-.105q.046-.058.08-.123q.035-.065.055-.136q.021-.071.028-.145q.007-.073-.001-.147q-.008-.073-.03-.144l-2.504-8.013q-1.219-3.657-4.754-5.025q-2.217-.858-4.394-.47q-1.019.084-1.873.567");
}

</style>
