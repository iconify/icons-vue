<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy-vizpgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-file-rename-rounded" /></template>
<style>
.hy-vizpgk {
  fill: currentColor;
  d: path("M11.283 16.5h5.833q.213 0 .356-.143q.144-.143.144-.357t-.144-.357t-.357-.143h-4.832zm-4.09 0h1.073q.161 0 .3-.056q.14-.055.27-.186L15.095 10q.148-.148.2-.31t.052-.323t-.064-.319t-.188-.308l-.925-.944q-.129-.129-.298-.193t-.335-.064q-.159 0-.319.061q-.16.062-.308.19l-6.282 6.258q-.13.13-.187.27t-.056.301v1.073q0 .349.23.578q.23.23.578.23m6.344-6.177l-.95-.95l.95-.95l.925.944zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
