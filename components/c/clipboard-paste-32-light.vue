<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t9rth7bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-paste-32-light" /></template>
<style>
.t9rth7bnk {
  fill: currentColor;
  d: path("M9.05 4a2.5 2.5 0 0 1 2.45-2h7a2.5 2.5 0 0 1 2.45 2h1.8A3.25 3.25 0 0 1 26 7.25v1.256a5 5 0 0 0-.25-.006H25V7.25A2.25 2.25 0 0 0 22.75 5h-1.8v.004A2.5 2.5 0 0 1 18.5 7h-7a2.5 2.5 0 0 1-2.45-2h-1.8A2.25 2.25 0 0 0 5 7.25v19.5A2.25 2.25 0 0 0 7.25 29h5.816c.196.365.439.7.72 1H7.25A3.25 3.25 0 0 1 4 26.75V7.25A3.25 3.25 0 0 1 7.25 4zM20 4.5A1.5 1.5 0 0 0 18.5 3h-7a1.5 1.5 0 0 0 0 3h7A1.5 1.5 0 0 0 20 4.5m-6 8.75A3.25 3.25 0 0 1 17.25 10h8.5A3.25 3.25 0 0 1 29 13.25v13.5A3.25 3.25 0 0 1 25.75 30h-8.5A3.25 3.25 0 0 1 14 26.75zM17.25 11A2.25 2.25 0 0 0 15 13.25v13.5A2.25 2.25 0 0 0 17.25 29h8.5A2.25 2.25 0 0 0 28 26.75v-13.5A2.25 2.25 0 0 0 25.75 11z");
}

</style>
