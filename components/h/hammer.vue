<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azcv6vbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hammer" /></template>
<style>
.azcv6vbai {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25q-2.25 0-2.25 2.25V7q0 2.25 2.25 2.25h3.438q-.188.531-.188 1.25v9q0 2.75 2.75 2.75t2.75-2.75v-9q0-.719-.188-1.25H14q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-.48q3.013-1.05 5.415.151q.133.067.282.077q.149.011.29-.036q.142-.048.254-.145q.113-.098.18-.232q.067-.133.077-.282q.011-.149-.036-.29Q19.541 2.25 14 2.25z");
}

</style>
