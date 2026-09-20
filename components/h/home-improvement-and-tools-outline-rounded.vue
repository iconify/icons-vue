<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyt8gd_3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-improvement-and-tools-outline-rounded" /></template>
<style>
.cyt8gd_3e {
  fill: currentColor;
  d: path("M11.702 20.195q-.136-.053-.267-.183l-.956-.956q-.217-.217-.348-.518T10 17.906V5.892L8.548 3.825q-.177-.27-.037-.547Q8.651 3 8.969 3h6.062q.318 0 .458.278t-.037.547L14 5.892v12.014q0 .332-.13.632t-.349.518l-.956.955q-.13.131-.27.184q-.139.053-.298.053t-.295-.053M11 10.5h2V5.6L14 4h-4l1 1.6zm2 1h-2v3h2zm0 6.577V15.5h-2v2.577l1 1zM12 15.5");
}

</style>
