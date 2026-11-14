<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbq3xnb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:directions-boat" /></template>
<style>
.fbq3xnb_f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 9.25H7.25v2.5h8.536l-1.25-2.5zm3.75-1.5H15q.104 0 .205.029q.1.028.189.083t.16.132t.117.171l1.793 3.585h1.382q1.346 0 2.087 1.123q.741 1.124.211 2.361l-1.5 3.5q-.649 1.516-2.298 1.516H6.654q-1.649 0-2.298-1.516l-1.5-3.5q-.53-1.237.211-2.361q.741-1.123 2.087-1.123h.596V8.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75V4.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q8.926 3.75 9 3.75h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-3 0h1.5v-2.5h-1.5z");
}

</style>
