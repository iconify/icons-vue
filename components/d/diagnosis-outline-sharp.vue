<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjm_cj5vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:diagnosis-outline-sharp" /></template>
<style>
.pjm_cj5vr {
  fill: currentColor;
  d: path("M8.5 17.73h7v-1h-7zm0-2.614h7v-1h-7zM12 12.28q1.535-1.385 2.517-2.24q.983-.854.983-2.072q0-.708-.496-1.204T13.8 6.27q-.679 0-1.041.309q-.363.308-.759.799q-.396-.49-.759-.799q-.362-.309-1.041-.309q-.708 0-1.204.496T8.5 7.97q0 1.217.945 2.035q.945.817 2.555 2.277M5 21V3h14v18zm1-1h12V4H6zm0 0V4z");
}

</style>
