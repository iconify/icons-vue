<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr006ibbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lockout-cable" /></template>
<style>
.cr006ibbe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.125 16.15q-2.448-1.414-3.411-4.072t.012-5.312t3.429-4.057t5.236-.895T15.974 4.5q1.573 1.904 1.753 4.302q2.271.338 2.273 2.947v2.115q2.25.505 2.25 3.261v1.75q0 3.375-3.375 3.375h-3.75q-3.375 0-3.375-3.375v-1.75q0-2.756 2.25-3.261V11.75q.002-2.587 2.233-2.942q-.283-4.638-5.111-5.519q-5.175-.944-6.988 3.994Q2.32 12.22 6.875 14.85q.064.037.12.086t.1.107q.045.059.078.125q.032.067.051.138q.02.071.024.145q.005.074-.004.147t-.034.143t-.06.134q-.075.129-.193.22t-.263.129t-.292.02q-.148-.02-.277-.094M18.5 11.751v1.999h-3v-2q.001-1.498 1.5-1.498t1.5 1.499");
}

</style>
