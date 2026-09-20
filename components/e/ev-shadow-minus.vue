<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1moi0spe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ev-shadow-minus" /></template>
<style>
.o1moi0spe {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12t.71-3.506t1.927-2.857T8.494 3.71Q10.137 3 12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12q0 .177-.015.376q-.016.199-.027.376q-.723-.573-1.592-.893t-1.86-.32q-2.289 0-3.9 1.598t-1.612 3.888q0 1.125.417 2.11q.416.984 1.143 1.727q-.388.069-.767.104Q12.407 21 12 21m-8-9q0 3.28 2.244 5.583q2.245 2.302 5.497 2.4q.211 0 .416-.01t.397-.048q-2.165-1.106-3.504-3.216T7.711 12T9.07 7.291t3.523-3.216q-.211-.039-.423-.048q-.211-.01-.423-.01q-3.258.092-5.502 2.397T4 12m10 5.539v-1h7v1z");
}

</style>
