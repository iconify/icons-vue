<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si8e-7bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-library-outline-rounded" /></template>
<style>
.si8e-7bsy {
  fill: currentColor;
  d: path("M4 17.073V9.789q0-.454.338-.745q.337-.29.79-.24q1.938.3 3.667 1.162T12 12.127q1.475-1.298 3.205-2.16t3.666-1.163q.454-.05.792.24q.337.29.337.745v7.284q0 .396-.265.69q-.266.293-.662.343q-1.754.269-3.263.835q-1.51.565-2.964 1.553q-.198.148-.405.213T12 20.77t-.441-.064t-.405-.213Q9.7 19.506 8.2 18.941t-3.273-.835q-.396-.05-.661-.344Q4 17.47 4 17.074m8 2.789q1.575-1.156 3.35-1.866t3.65-.934V9.776q-1.96.325-3.741 1.264T12 13.458q-1.477-1.477-3.259-2.417T5 9.777v7.285q1.875.225 3.65.934T12 19.862M9.714 7.632q-.945-.943-.945-2.286t.944-2.286T12 2.116t2.286.944t.945 2.286t-.944 2.287T12 8.577t-2.286-.944m3.862-.711q.655-.655.655-1.576t-.655-1.576T12 3.116t-1.576.654t-.655 1.576t.655 1.576q.655.655 1.576.655t1.576-.655M12 13.458");
}

</style>
