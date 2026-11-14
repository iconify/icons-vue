<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwybh8s2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-arsenic" /></template>
<style>
.hwybh8s2w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.077 11.17q-.876 1.751-.361 3.64l.398 1.459q.776 2.844 3.624 3.604l3.59.958q1.732.462 3.375-.257l4.319-1.89q2.669-1.167 3.031-4.059l.411-3.291q.328-2.625-1.622-4.413L17.12 4.425q-1.889-1.732-4.408-1.259l-3.715.697q-2.501.469-3.64 2.745zm9.285-4.657q.146-.028.292.003t.27.115q.123.084.204.209q.082.125.109.272q.014.072.013.146t-.016.146q-.015.073-.044.141t-.071.129q-.042.06-.095.112q-.052.052-.114.092q-.062.041-.131.068q-.068.028-.141.041q-3.462.649-3.894 4.106q-.009.073-.032.143q-.024.071-.06.135q-.037.064-.085.12t-.107.101t-.124.078q-.066.034-.137.053q-.071.02-.145.025t-.147-.004t-.143-.032q-.071-.024-.135-.06q-.064-.037-.12-.085t-.101-.107t-.078-.124t-.053-.137t-.025-.145t.004-.147q.568-4.543 5.106-5.394");
}

</style>
