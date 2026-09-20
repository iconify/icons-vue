<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd2evabdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-paint-sharp" /></template>
<style>
.xd2evabdr {
  fill: currentColor;
  d: path("M9.962 21v-6.212H5V6.596q0-1.07.774-1.833T7.634 4H19v10.789h-4.98V21zM6 10.462h12V5h-1.634v3.712h-1V5h-1.847v1.962h-1V5H7.635q-.69 0-1.163.453Q6 5.906 6 6.596z");
}

</style>
