<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lpkizn9an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-48-filled" /></template>
<style>
.lpkizn9an {
  fill: currentColor;
  d: path("M35.001 24C41.076 24 46 28.924 46 34.999s-4.924 10.999-10.999 10.999c-1.865 0-3.663-.465-5.26-1.337l-4.52 1.302a.957.957 0 0 1-1.184-1.185l1.303-4.516A10.95 10.95 0 0 1 24 34.999C24 28.924 28.925 24 35 24m6.999.043A12.94 12.94 0 0 0 35.001 22c-7.18 0-13 5.82-13 12.999c0 1.91.415 3.766 1.2 5.461L22.757 42H12.25A6.25 6.25 0 0 1 6 35.75V16.5h36zM31 36a1 1 0 1 0 0 2h5a1 1 0 1 0 0-2zm0-4a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2zm4.75-26A6.25 6.25 0 0 1 42 12.25V14H6v-1.75A6.25 6.25 0 0 1 12.25 6z");
}

</style>
