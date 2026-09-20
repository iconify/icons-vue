<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nxj0a4_ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-32-regular" /></template>
<style>
.nxj0a4_ql {
  fill: currentColor;
  d: path("M12.816 2.318a4.5 4.5 0 0 1 6.364 0l10.5 10.499a4.5 4.5 0 0 1 0 6.363l-10.5 10.499a4.5 4.5 0 0 1-6.364 0L2.318 19.18a4.5 4.5 0 0 1 0-6.363zm4.95 1.414a2.5 2.5 0 0 0-3.535 0L3.73 14.23a2.5 2.5 0 0 0 0 3.535l10.5 10.499a2.5 2.5 0 0 0 3.535 0l10.5-10.5a2.5 2.5 0 0 0 0-3.534zm-.973 5.061a1 1 0 0 1 1.415 0l3.5 3.5a1 1 0 0 1 0 1.414l-3.5 3.5a1 1 0 0 1-1.415-1.414L18.586 14H16.5a2.5 2.5 0 0 0-2.5 2.5V21a1 1 0 0 1-2 0v-4.5a4.5 4.5 0 0 1 4.5-4.5h2.086l-1.793-1.793a1 1 0 0 1 0-1.414");
}

</style>
