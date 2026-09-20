<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh35djbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-score" /></template>
<style>
.nh35djbyk {
  fill: currentColor;
  d: path("M9.74 19H4.617q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v4.576h-1.802l-4.556 4.556l-2.85-2.839l-4.07 4.072zm4.902 1.539l-3.557-3.558l.707-.708l2.85 2.839l5.689-5.689l.708.72zM4 8.808v2.384h16V8.808z");
}

</style>
