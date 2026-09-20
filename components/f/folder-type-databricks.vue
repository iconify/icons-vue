<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jyt1zj_pu"/><path class="ullrw9i0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-databricks" /></template>
<style>
.jyt1zj_pu {
  fill: var(--svg-color--732017, #732017);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.ullrw9i0j {
  fill: var(--svg-color--ff3621, #ff3621);
  d: path("M13.741 13.623v.563l8.629 4.869l7.707-4.353v1.76L22.37 20.84l-8.195-4.656l-.435.242v3.368l8.63 4.857l7.707-4.336v1.745l-7.707 4.379l-8.195-4.657l-.435.242v.571l8.63 4.855L31 22.595v-3.372l-.44-.24l-8.19 4.657l-7.709-4.381v-1.735l7.709 4.331L31 17v-3.324l-.44-.241l-8.19 4.657l-7.313-4.155l7.313-4.131l6.024 3.403l.527-.296v-.464L22.37 8.75Z");
}

</style>
