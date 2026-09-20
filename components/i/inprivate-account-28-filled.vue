<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vouij2b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:inprivate-account-28-filled" /></template>
<style>
.vouij2b7q {
  fill: currentColor;
  d: path("M23.83 18A3 3 0 0 0 21 16H7a3 3 0 0 0-3 3v.715C4 23.433 8.21 26 14 26c3.062 0 5.682-.757 7.471-2H14v-1h8.634c.427-.461.763-.964.995-1.5H14v-1h9.93a4.5 4.5 0 0 0 .07-.785V19H14v-1zM20 8q0-.381-.046-.75H14v-1h5.74a6 6 0 0 0-.696-1.5H14v-1h4.235a6 6 0 1 0 0 8.5H14v-1h5.044c.298-.46.534-.964.697-1.5H14v-1h5.954Q20 8.381 20 8");
}

</style>
