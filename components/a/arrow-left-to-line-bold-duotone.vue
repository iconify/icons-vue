<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-h9o8md"/><path class="eclqm_bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-to-line-bold-duotone" /></template>
<style>
.eclqm_bbe {
  fill: currentColor;
  d: path("M3 11.25L14.0684 11.25L11.1191 8.5537C10.8135 8.27427 10.792 7.79984 11.0713 7.49413C11.3507 7.1885 11.8252 7.16699 12.1309 7.44628L16.5059 11.4463C16.6613 11.5884 16.75 11.7894 16.75 12C16.75 12.2106 16.6613 12.4116 16.5059 12.5537L12.1309 16.5537C11.8251 16.833 11.3507 16.8115 11.0713 16.5059C10.792 16.2001 10.8135 15.7257 11.1191 15.4463L14.0684 12.75L3 12.75C2.58579 12.75 2.25 12.4142 2.25 12C2.25 11.5858 2.58579 11.25 3 11.25Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wl-h9o8md {
  fill: currentColor;
  d: path("M21.75 4C21.75 3.58579 21.4142 3.25 21 3.25C20.5858 3.25 20.25 3.58579 20.25 4L20.25 20C20.25 20.4142 20.5858 20.75 21 20.75C21.4142 20.75 21.75 20.4142 21.75 20L21.75 4Z");
}

</style>
