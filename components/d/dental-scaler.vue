<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj60f-b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-scaler" /></template>
<style>
.cj60f-b1l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.995 13.065l3.035-3.035q.106-.105.163-.243t.057-.287q0-2.621 1.412-4.261Q17.945 3.75 19.75 3.75q.283 0 .401.144q.144.176.131.547q-.043 1.166-1.276 2.245q-.112.098-.178.232q-.066.133-.076.282t.038.29q.047.142.146.254q.048.055.107.101q.058.045.125.077q.066.033.137.052t.145.024t.147-.004t.143-.034q.07-.023.134-.06t.12-.086q1.72-1.504 1.787-3.317q.035-.939-.471-1.555q-.568-.692-1.56-.692q-2.493 0-4.225 2.011q-1.686 1.958-1.771 4.924l-2.819 2.82q-.64-.376-1.435-.376q-1.189 0-2.03.841l-3.5 3.5q-.841.841-.841 2.03t.841 2.03t2.03.841t2.03-.841l3.5-3.5q.841-.841.841-2.03q0-.795-.376-1.435");
}

</style>
