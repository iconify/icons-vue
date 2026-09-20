<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx4sllhyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:landscape-2-off-rounded" /></template>
<style>
.cx4sllhyk {
  fill: currentColor;
  d: path("M20.555 21.796q-.191 0-.357-.165L2.394 3.82q-.146-.146-.156-.347t.156-.366t.357-.166t.357.166l17.81 17.81q.145.145.152.347t-.159.366q-.165.165-.356.165M6.135 9.904q-1.02 0-1.75-.724q-.731-.724-.731-1.738q0-.78.429-1.388q.428-.608 1.098-.873l3.196 3.196q-.266.67-.873 1.098q-.608.429-1.37.429m13.715 6.849q-.28-.012-.497-.23L11.977 9.16q-.162-.162-.205-.376q-.043-.215.012-.432l.089-.279q.311-.988 1.155-1.57q.843-.58 1.862-.58q1.014 0 1.851.568t1.155 1.526l2.779 7.649q.125.298.007.562t-.336.4q-.217.138-.497.125M3.487 19q-.46 0-.7-.388t-.028-.793l2.264-4.334q.212-.404.588-.637t.835-.233q.485 0 .889.255t.59.715l.521 1.226q.185.4.687.369t.648-.432l1.198-3.77L19 19z");
}

</style>
