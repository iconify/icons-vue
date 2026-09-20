<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qr1az5wkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:closed-captioning-light" /></template>
<style>
.qr1az5wkx {
  fill: currentColor;
  d: path("M224 50H32a14 14 0 0 0-14 14v128a14 14 0 0 0 14 14h192a14 14 0 0 0 14-14V64a14 14 0 0 0-14-14m2 142a2 2 0 0 1-2 2H32a2 2 0 0 1-2-2V64a2 2 0 0 1 2-2h192a2 2 0 0 1 2 2Zm-108.81-39.29a6 6 0 0 1-2.19 8.2a38 38 0 1 1 0-65.82a6 6 0 1 1-6 10.38a26 26 0 1 0 0 45.05a6 6 0 0 1 8.19 2.19m80 0a6 6 0 0 1-2.19 8.2a38 38 0 1 1 0-65.82a6 6 0 1 1-6 10.38a26 26 0 1 0 0 45.05a6 6 0 0 1 8.19 2.19");
}

</style>
