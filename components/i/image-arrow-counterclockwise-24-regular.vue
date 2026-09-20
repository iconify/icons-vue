<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgpoo8qzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-arrow-counterclockwise-24-regular" /></template>
<style>
.tgpoo8qzl {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75v-5.771c.463.296.967.535 1.5.708v5.063q.002.313.104.594l5.822-5.701a2.25 2.25 0 0 1 3.02-.117l.128.118l5.823 5.7q.102-.279.103-.594V6.25a1.75 1.75 0 0 0-1.75-1.75h-5.063a6.5 6.5 0 0 0-.708-1.5zm-5.226 10.715a.75.75 0 0 0-.965-.071l-.083.07l-5.808 5.687q.275.098.582.099h11.5q.306-.002.58-.099zM6.5 1a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m8.752 5.5a2.252 2.252 0 1 1 0 4.504a2.252 2.252 0 0 1 0-4.504M6.501 3A3.5 3.5 0 0 0 4 4.05V3.5a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1h-.999a2.5 2.5 0 1 1 .179 3.214A.64.64 0 0 0 4.222 8c-.41 0-.672.427-.409.742A3.5 3.5 0 1 0 6.501 3m8.751 5a.752.752 0 1 0 0 1.504a.752.752 0 0 0 0-1.504");
}

</style>
