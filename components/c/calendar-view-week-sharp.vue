<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyix29btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-view-week-sharp" /></template>
<style>
.eyix29btp {
  fill: currentColor;
  d: path("M12.442 18.23V5.77h3.452v12.46zm-4.336 0V5.77h3.452v12.46zm-4.337 0V5.77h3.452v12.46zm13.01 0V5.77h3.452v12.46z");
}

</style>
