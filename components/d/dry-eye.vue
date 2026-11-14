<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8k0kcf5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dry-eye" /></template>
<style>
.x8k0kcf5c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.869 9.094Q5.305 3.75 10 3.75t8.131 5.344q.058.091.089.195q.03.103.03.211t-.03.211t-.089.195Q14.695 15.25 10 15.25T1.869 9.906q-.058-.091-.089-.195q-.03-.103-.03-.211t.03-.211t.089-.195M10 6.25q-3.25 0-3.25 3.25T10 12.75t3.25-3.25T10 6.25m8.564 7.256Q21.75 17.147 21.75 19q0 3.5-3.75 3.5T14.25 19q0-1.853 3.186-5.494q.098-.112.232-.178q.133-.066.282-.076t.29.038q.142.047.254.146q.038.032.07.07M15.75 19q0-1.153 2.25-3.847q2.25 2.694 2.25 3.847q0 2-2.25 2t-2.25-2");
}

</style>
