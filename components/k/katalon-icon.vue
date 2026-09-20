<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":393};
const content = `<path class="qef7669wi"/><path class="kir1pdbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:katalon-icon" /></template>
<style>
.kir1pdbpt {
  d: path("M128.001 0L0 130.725v130.726h128.001l127.958-130.726V0z");
}

.qef7669wi {
  fill: var(--svg-color--19d89f, #19d89f);
  d: path("M256 261.407H127.998v130.725H256z");
}

</style>
