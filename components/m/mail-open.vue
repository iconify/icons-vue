<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htmkvfbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mail-open" /></template>
<style>
.htmkvfbri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.584 3.376l-9 6q-.077.051-.139.12q-.063.068-.106.15q-.044.082-.066.172T2.25 10v8q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75v-8q0-.093-.023-.182q-.022-.09-.066-.172q-.043-.082-.106-.15q-.062-.069-.139-.12l-9-6q-.092-.062-.199-.094q-.106-.032-.217-.032t-.217.032t-.199.094M12 14.63l8.12-4.776q.128-.076.276-.097q.148-.02.292.017q.145.037.264.127t.194.219q.038.063.062.133q.025.07.035.143t.006.147t-.023.145t-.051.138t-.076.126q-.045.059-.1.108t-.119.086l-8.5 5q-.086.051-.183.078q-.097.026-.197.026t-.197-.026q-.097-.027-.183-.078l-8.5-5q-.064-.037-.119-.086t-.1-.108q-.044-.059-.076-.126q-.032-.066-.051-.138q-.019-.071-.023-.145t.006-.147t.035-.143t.062-.133q.075-.129.194-.219t.264-.127t.292-.017t.276.097z");
}

</style>
