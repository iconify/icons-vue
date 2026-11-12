<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypoaftbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:earbuds-fill-round" /></template>
<style>
.ypoaftbar {
  fill: currentColor;
  d: path("M11 7v13c0 .571-.286 1.08-.758 1.395c-.924.615-2.433.443-3.02-.563A1.65 1.65 0 0 1 7 20v-9H6c-1.079 0-2.172-.259-2.957-1.043C2.259 9.172 2 8.079 2 7s.259-2.172 1.043-2.957C3.828 3.259 4.921 3 6 3c1.706 0 3.617.636 4.52 2.184c.322.551.48 1.179.48 1.816m7 4h-1v9c0 .292-.075.579-.222.832c-.587 1.006-2.096 1.178-3.02.563A1.67 1.67 0 0 1 13 20V7c0-.637.158-1.265.48-1.816C14.383 3.636 16.294 3 18 3c1.079 0 2.172.259 2.957 1.043C21.741 4.828 22 5.921 22 7s-.259 2.172-1.043 2.957C20.172 10.741 19.079 11 18 11M6.01 6H6a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m12 0H18a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
