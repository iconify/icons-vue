<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-egyh5-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gavel-outline" /></template>
<style>
.t-egyh5-e {
  fill: currentColor;
  d: path("M4.116 20.5v-1h11v1zm5.957-5.466l-4.958-4.957l1.408-1.458l5.008 4.958zm5.504-5.503l-4.958-5.008l1.458-1.407l4.958 4.957zm5.023 9.777L8.242 6.95l.708-.708L21.308 18.6z");
}

</style>
