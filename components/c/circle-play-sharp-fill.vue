<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lldnthb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-play-sharp-fill" /></template>
<style>
.lldnthb1q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 17.937 17.937 23 12 23C6.063 23 1 17.937 1 12C1 6.063 6.063 1 12 1C17.937 1 23 6.063 23 12ZM9.4927 6.4533L17.0107 11.152C17.6374 11.5437 17.6374 12.4563 17.0107 12.848L9.4927 17.5467C8.8266 17.963 7.9627 17.4841 7.9627 16.6987L7.9627 7.3013C7.9627 6.5159 8.8266 6.037 9.4927 6.4533Z");
}

</style>
