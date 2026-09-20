<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l978qsbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:incomplete-circle-outline-rounded" /></template>
<style>
.l978qsbkv {
  fill: currentColor;
  d: path("M12.003 21q-1.866 0-3.51-.709q-1.643-.708-2.859-1.923T3.709 15.51T3 12q0-1.87.698-3.499t1.933-2.87L12 12V3q1.864 0 3.507.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
