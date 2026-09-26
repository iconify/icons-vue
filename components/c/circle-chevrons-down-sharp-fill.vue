<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svc3u7xlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-down-sharp-fill" /></template>
<style>
.svc3u7xlm {
  fill: currentColor;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM15.0858 12.2501L12 15.3359L8.9141 12.2502L7.5001 13.6642L11.293 17.457C11.6835 17.8475 12.3165 17.8475 12.707 17.457L16.4998 13.6641L15.0858 12.2501ZM15.0858 6.2501L12 9.3359L8.9141 6.2502L7.5001 7.6642L11.293 11.457C11.6835 11.8475 12.3165 11.8475 12.707 11.457L16.4998 7.6641L15.0858 6.2501Z");
}

</style>
