<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbteqomwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:doorbell-sharp" /></template>
<style>
.tbteqomwj {
  fill: currentColor;
  d: path("M12.626 16.991q.259-.239.297-.606h-1.846q.039.367.297.606q.259.24.626.24t.626-.24m-4.318-1.106h7.384v-.77h-1v-2.272q0-1.064-.532-1.934q-.533-.87-1.525-1.14v-.961h-1.27v.961q-.992.27-1.524 1.14q-.533.87-.533 1.934v2.273h-1zM5 20V9.5l7-5.27l7 5.27V20z");
}

</style>
