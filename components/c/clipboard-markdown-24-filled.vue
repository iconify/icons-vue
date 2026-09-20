<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy38qcb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-markdown-24-filled" /></template>
<style>
.cy38qcb4u {
  fill: currentColor;
  d: path("M13.75 2a2.25 2.25 0 0 1 2.236 2h1.764A2.25 2.25 0 0 1 20 6.25v7.92a1.75 1.75 0 0 0-2.5 1.58v1.42a1.76 1.76 0 0 0-1.5-.001V15.75a1.75 1.75 0 0 0-3.315-.782L11.5 17.337l-1.185-2.37A1.75 1.75 0 0 0 7 15.75v5.5c0 .269.063.522.17.75h-.92A2.25 2.25 0 0 1 4 19.75V6.25A2.25 2.25 0 0 1 6.25 4h1.764a2.25 2.25 0 0 1 2.236-2zm.672 13.02a.75.75 0 0 1 .578.73v5.5a.75.75 0 0 1-1.5 0v-2.323l-1.33 2.658a.75.75 0 0 1-1.34 0L9.5 18.927v2.323a.75.75 0 0 1-1.5 0v-5.5a.75.75 0 0 1 1.42-.335l2.08 4.158l2.08-4.158a.75.75 0 0 1 .842-.394M19.25 15a.75.75 0 0 1 .75.75v3.69l1.22-1.22a.75.75 0 1 1 1.06 1.06l-2.5 2.5a.75.75 0 0 1-1.06 0l-2.5-2.5a.75.75 0 1 1 1.06-1.06l1.22 1.22v-3.69a.75.75 0 0 1 .75-.75m-9-11.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5z");
}

</style>
