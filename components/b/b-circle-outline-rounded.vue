<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdqx5jysy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:b-circle-outline-rounded" /></template>
<style>
.wdqx5jysy {
  fill: currentColor;
  d: path("M10.058 17.039h2.384q1.5 0 2.354-.75t.854-2.1q0-1.003-.499-1.61t-1.507-.812v-.05q.789-.184 1.242-.783q.455-.6.455-1.463q0-1.292-.806-1.904t-2.475-.611h-2.002q-.348 0-.578.23t-.23.577v8.468q0 .348.23.578t.578.23m.134-5.678V7.852h1.868q1.215 0 1.77.413t.555 1.316q0 .886-.543 1.334q-.542.447-1.644.447zm0 4.793v-3.925h2.037q1.227 0 1.83.465q.605.465.605 1.433q0 .98-.596 1.504t-1.74.523zm-1.698 4.145q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.71-3.506t1.927-2.867t2.857-1.926T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.701 3.506t-1.926 2.857t-2.867 1.926T12 21t-3.506-.701m9.178-2.636Q20 15.325 20 12t-2.337-5.663T12 4T6.337 6.328T4 12t2.328 5.672T12 20t5.672-2.337M12 12");
}

</style>
