<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmjdr-22g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:google-home-devices-outline" /></template>
<style>
.tmjdr-22g {
  fill: currentColor;
  d: path("M8.5 20v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V7.23h-1V5.616q0-.27-.173-.443T19.384 5H4.616q-.27 0-.443.173T4 5.616v10.769q0 .269.173.442t.443.173h6.769v3zm7.27-5.23q.582-.581 1.422-.581t1.423.581t.581 1.422t-.582 1.423t-1.422.581t-1.422-.582t-.581-1.422q0-.84.581-1.422M20.154 9q.367 0 .607.24q.239.239.239.606v9.308q0 .367-.24.607q-.239.239-.606.239H14.23q-.367 0-.607-.24q-.24-.239-.24-.606V9.846q0-.367.24-.607q.24-.239.607-.239zm-3.873 1.204q-.358.357-.358.911t.358.912t.911.358t.912-.358t.358-.912t-.358-.911t-.912-.358t-.911.358m3.014 8.091q.859-.858.859-2.103t-.859-2.102q-.858-.86-2.103-.86t-2.102.86q-.86.858-.86 2.102t.86 2.103t2.102.859t2.103-.859");
}

</style>
