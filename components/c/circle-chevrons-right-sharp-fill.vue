<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhopss1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-right-sharp-fill" /></template>
<style>
.thhopss1e {
  fill: currentColor;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM6.2502 8.9142L9.3359 12L6.2502 15.0859L7.6642 16.4999L11.457 12.707C11.8475 12.3165 11.8475 11.6835 11.457 11.293L7.6642 7.5002L6.2502 8.9142ZM12.2502 8.9142L15.3359 12L12.2502 15.0859L13.6642 16.4999L17.457 12.707C17.8475 12.3165 17.8475 11.6835 17.457 11.293L13.6642 7.5002L12.2502 8.9142Z");
}

</style>
