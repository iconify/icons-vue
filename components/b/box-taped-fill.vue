<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd22smb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-fill" /></template>
<style>
.xd22smb-t {
  fill: currentColor;
  d: path("m9.758 3.107l-1.129-.558l2.485-1.227a2 2 0 0 1 .872-.207h.028c.303.003.6.073.872.207l8.004 3.953q.054.027.106.056l-3.367 1.663ZM8.629 4.78l6.742 3.329L12 9.774L3.004 5.331q.052-.03.106-.056l.004-.002l3.257-1.608ZM11 11.51v11.111l-7.886-3.894A2 2 0 0 1 2 16.934V7.066Zm2 0l9-4.444v9.868a2 2 0 0 1-1.114 1.793L13 22.621Z");
}

</style>
