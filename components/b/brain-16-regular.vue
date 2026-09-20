<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u-9y6ybdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:brain-16-regular" /></template>
<style>
.u-9y6ybdx {
  fill: currentColor;
  d: path("M9.75 1c1.175 0 2.137.9 2.24 2.048A2.5 2.5 0 0 1 14 5.5a2.5 2.5 0 0 1-.826 1.852a2.956 2.956 0 0 1-.207 5.537A2.5 2.5 0 0 1 10.5 15h-.25A2.74 2.74 0 0 1 8 13.827A2.74 2.74 0 0 1 5.75 15H5.5a2.5 2.5 0 0 1-2.467-2.111a2.956 2.956 0 0 1-.207-5.537A2.5 2.5 0 0 1 2 5.5a2.5 2.5 0 0 1 2.01-2.452A2.249 2.249 0 0 1 8 1.836A2.25 2.25 0 0 1 9.75 1m-3.5 1C5.56 2 5 2.56 5 3.25v.25a.5.5 0 0 1-.5.5a1.5 1.5 0 1 0 0 3a.5.5 0 0 1 .082.993l-.946.158a1.957 1.957 0 0 0-.154 3.83l.14.034A.5.5 0 0 1 4 12.5A1.5 1.5 0 0 0 5.5 14h.25a1.75 1.75 0 0 0 1.75-1.75v-9C7.5 2.56 6.94 2 6.25 2m3.5 0c-.69 0-1.25.56-1.25 1.25v9c0 .966.784 1.75 1.75 1.75h.25a1.5 1.5 0 0 0 1.5-1.5a.5.5 0 0 1 .379-.485l.139-.035a1.958 1.958 0 0 0-.154-3.829l-.946-.158A.5.5 0 0 1 11.5 7a1.5 1.5 0 0 0 0-3a.5.5 0 0 1-.5-.5v-.25C11 2.56 10.44 2 9.75 2");
}

</style>
