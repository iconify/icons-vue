<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p_fla0bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-off-16-filled" /></template>
<style>
.p_fla0bia {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.707l-1.16-1.16A1.5 1.5 0 0 1 11.5 15h-7A1.5 1.5 0 0 1 3 13.5V3.707L1.146 1.854a.5.5 0 0 1 0-.708M9.5 1a1.5 1.5 0 0 1 1.415 1h.585A1.5 1.5 0 0 1 13 3.5v7.379l-8.84-8.84q.165-.038.34-.039h.585A1.5 1.5 0 0 1 6.5 1zm-3 1a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
