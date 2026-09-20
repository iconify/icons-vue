<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ussuonb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-arrow-left-16-filled" /></template>
<style>
.ussuonb8f {
  fill: currentColor;
  d: path("M1 4.5A2.5 2.5 0 0 1 3.5 2h2.086a1.5 1.5 0 0 1 1.06.44L8 3.792l-2.06 2.06A.5.5 0 0 1 5.585 6H1zM1 7v4.5A2.5 2.5 0 0 0 3.5 14h3.1A5.5 5.5 0 0 1 15 7.257V6.5A2.5 2.5 0 0 0 12.5 4H9.207l-2.56 2.56A1.5 1.5 0 0 1 5.585 7zm10.5 9a4.5 4.5 0 1 1 0-9a4.5 4.5 0 0 1 0 9m-2.353-4.854l-.003.003a.5.5 0 0 0-.144.348v.006a.5.5 0 0 0 .146.35l2 2a.5.5 0 0 0 .708-.707L10.707 12H13.5a.5.5 0 0 0 0-1h-2.793l1.147-1.146a.5.5 0 0 0-.708-.708z");
}

</style>
