<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ap_44-0es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-trigger-left-20-filled" /></template>
<style>
.ap_44-0es {
  fill: currentColor;
  d: path("M14.36 2c1.497 0 2.967.817 3.274 2.438C17.84 5.529 18 7.03 18 9c0 2.62-.92 4.88-2.592 6.485C13.738 17.09 11.358 18 8.5 18c-.929 0-2.877.088-4.237-.197a1.6 1.6 0 0 1-.86-.461a1.56 1.56 0 0 1-.395-.805c-.103-.568.056-1.197.344-1.73C4.123 13.38 5 11.506 5 9.5c0-1.557-.251-3.237-1.169-5.26C3.381 3.244 4.054 2 5.223 2zM8.5 7a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H9V7.5a.5.5 0 0 0-.5-.5m3 0a.5.5 0 0 0 0 1h1v3.5a.5.5 0 0 0 1 0V8h1a.5.5 0 0 0 0-1z");
}

</style>
