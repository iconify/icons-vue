<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="kuiy7mb2v"><path class="i6ljr2bxz"/><path class="fqtpnu0hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aave" /></template>
<style>
.fqtpnu0hu {
  d: path("M12 7.5c-4.971 0-9.001 3.937-9 8.792h2.3c0-3.638 2.976-6.588 6.7-6.588s6.7 2.95 6.7 6.588H21c0-4.855-4.03-8.792-9-8.792");
}

.i6ljr2bxz {
  d: path("M9.61 16.5c1.012 0 1.831-.786 1.831-1.755c0-.97-.82-1.755-1.83-1.755c-1.012 0-1.831.786-1.831 1.755c0 .97.82 1.755 1.83 1.755m4.786 0c1.01 0 1.83-.786 1.83-1.755c0-.97-.82-1.755-1.83-1.755s-1.831.786-1.831 1.755c0 .97.82 1.755 1.83 1.755");
}

.kuiy7mb2v {
  fill: var(--svg-color--9391f7, #9391f7);
}

</style>
