<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h2wowwb4y"/><path class="bep-stbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-qatar" /></template>
<style>
.bep-stbyn {
  fill: var(--svg-color--eee, #EEE);
  d: path("M11 28.111l5.295-1.444L11 25.222l5.295-1.444L11 22.333l5.295-1.444L11 19.444L16.295 18L11 16.556l5.295-1.444L11 13.667l5.295-1.444L11 10.778l5.295-1.445L11 7.889l5.295-1.444L11 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h7l5.295-1.444L11 28.111z");
}

.h2wowwb4y {
  fill: var(--svg-color--8d1b3d, #8D1B3D);
  d: path("M32 5H11v26h21a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

</style>
