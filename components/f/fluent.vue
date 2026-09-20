<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpzf-5sag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fluent" /></template>
<style>
.wpzf-5sag {
  d: path("M20.998 6.36V4H3v2.36h8.01a16.6 16.6 0 0 0-4.006 3.281H3v2.36h2.256A15.33 15.33 0 0 0 3 20h2.473c0-2.988 1.014-5.752 2.727-8h4.675c-2.419 1.902-3.965 4.783-3.965 8h2.473c0-4.413 3.76-8 8.38-8H21V9.64H10.485c2.499-2.043 5.74-3.281 9.278-3.281H21z");
}

</style>
