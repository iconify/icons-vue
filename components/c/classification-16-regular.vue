<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n0ij5cckz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:classification-16-regular" /></template>
<style>
.n0ij5cckz {
  fill: currentColor;
  d: path("M12.87 1a2.128 2.128 0 0 1 1.18 3.9l-2.948 1.963l1.572 1.572l.172.19c.8.982.743 2.43-.172 3.346l-1.732 1.731a1 1 0 0 1-1.414 0l-.316-.316l-1.17 1.17a1.5 1.5 0 0 1-2.121 0l-4.482-4.482a1.5 1.5 0 0 1-.103-2.006l.103-.115l1.17-1.17l-.316-.317a1 1 0 0 1 0-1.414l1.73-1.73a2.5 2.5 0 0 1 3.537 0l1.573 1.573l1.966-2.947A2.13 2.13 0 0 1 12.87 1M2.146 8.66l-.064.08a.5.5 0 0 0 .064.627l4.482 4.483a.5.5 0 0 0 .707 0l1.17-1.171l-5.189-5.19zm4.707-4.632a1.5 1.5 0 0 0-2.122 0L3 5.758l7.235 7.236l1.732-1.73a1.5 1.5 0 0 0 .102-2.008l-.102-.113zM12.87 2c-.377 0-.73.189-.94.503L9.855 5.615l.527.528l3.115-2.076A1.128 1.128 0 0 0 12.87 2");
}

</style>
