<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nml13yb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:earth-orbit-sun" /></template>
<style>
.nml13yb2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.983 10.091q.897 4.127-1.634 7.509q-2.532 3.381-6.745 3.682q-4.214.302-7.201-2.685t-2.685-7.201Q3.019 7.183 6.4 4.651q3.382-2.531 7.509-1.634q.146.032.269.117q.122.085.203.21q.081.126.107.273q.027.147-.005.292q-.016.073-.045.14q-.03.068-.072.129q-.042.06-.095.112q-.053.051-.115.091t-.131.067t-.142.04t-.146.012t-.146-.017q-3.459-.752-6.292 1.369t-3.085 5.651t2.25 6.033t6.033 2.25q3.53-.252 5.651-3.085t1.369-6.292q-.016-.072-.017-.146t.012-.146q.013-.073.04-.142t.067-.131t.091-.115q.052-.053.112-.095t.129-.072q.067-.029.14-.045q.145-.032.292-.005q.147.026.273.107q.125.081.21.203t.117.269M15.25 6q0-2.75 2.75-2.75T20.75 6T18 8.75T15.25 6M12 8q-4 0-4 4t4 4t4-4q0-1.657-1.172-2.828Q13.657 8 12 8");
}

</style>
