<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zso57wbcq"/><path class="cnk0oiz1l"/><path class="rfwiax37e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-circleci-opened" /></template>
<style>
.cnk0oiz1l {
  fill: var(--svg-color--7bc2db, #7bc2db);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.rfwiax37e {
  fill: var(--svg-color--064c64, #064c64);
  d: path("M17.944 20.5a2.5 2.5 0 1 1 2.5 2.5a2.5 2.5 0 0 1-2.5-2.5m2.5-10.5a10.51 10.51 0 0 0-10.173 7.9a.3.3 0 0 0-.01.1a.5.5 0 0 0 .5.5h4.231a.48.48 0 0 0 .45-.294a5.5 5.5 0 1 1 0 4.574a.51.51 0 0 0-.45-.294h-4.229a.5.5 0 0 0-.5.5c0 .031.01.063.01.1A10.5 10.5 0 1 0 20.443 10Z");
}

.zso57wbcq {
  fill: var(--svg-color--7bc2db, #7bc2db);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

</style>
