<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tpi7m7m5u"/><path class="q53fpubpn"/><path class="r63dkw7-j"/><path class="m-7kudboi"/><path class="gx_y8cbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-opentofu" /></template>
<style>
.gx_y8cbqb {
  fill: var(--svg-color--0d1a2a, #0d1a2a);
  d: path("M8.68 19.68v.02L6.4 18.5v-.02c.06-.72.61-1.03 1.24-.69s1.1 1.18 1.05 1.9m3.6 2.07L10 20.58v-.02c.06-.7.61-1.02 1.24-.68s1.1 1.17 1.05 1.89");
}

.m-7kudboi {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.75 10.95a.45.45 0 0 1 .66.4v10.62a.5.5 0 0 1-.23.4l-9.75 5.36a.45.45 0 0 1-.67-.4V16.7q.01-.25.23-.39z");
}

.q53fpubpn {
  fill: var(--svg-color--e6c220, #e6c220);
  d: path("M15.78 3.6a.5.5 0 0 1 .44 0l9.66 5.32a.45.45 0 0 1 0 .79l-9.67 5.31a.5.5 0 0 1-.43 0L6.12 9.71a.45.45 0 0 1 0-.8z");
}

.r63dkw7-j {
  fill: var(--svg-color--feda15, #feda15);
  d: path("M4.59 11.35a.45.45 0 0 1 .66-.4l9.76 5.36q.22.15.23.4v10.63a.45.45 0 0 1-.67.39l-9.75-5.36a.5.5 0 0 1-.23-.39z");
}

.tpi7m7m5u {
  fill: var(--svg-color--0d1a2a, #0d1a2a);
  d: path("M16.95 2.29a2 2 0 0 0-1.9 0L5.4 7.59l-.02.02l-1.27.7a2 2 0 0 0-1.02 1.71v11.94A2 2 0 0 0 4.1 23.7l9.75 5.37l.05.01l1.16.64c.58.33 1.3.33 1.89 0l1.16-.64l.04-.01l9.76-5.37a2 2 0 0 0 1.01-1.71V10.02a2 2 0 0 0-1.01-1.71l-1.27-.7h-.03zM17.57 16l9.03-4.97l.03-.01l.12-.06a.45.45 0 0 1 .66.39v9.3a.45.45 0 0 1-.66.4l-.1-.05l-.05-.03zM5.36 11.01l.03.02l9.04 4.96l-9.03 4.98l-.06.03l-.09.04a.45.45 0 0 1-.66-.39v-9.3a.45.45 0 0 1 .66-.4zm20.53-2.08l-8.46-4.67a.45.45 0 0 0-.68.39v10.08l9.14-5.02a.45.45 0 0 0 0-.79M6.11 9.7l9.13 5.02V4.65a.45.45 0 0 0-.66-.39L6.1 8.92a.45.45 0 0 0 0 .78m0 13.38a.45.45 0 0 1-.02-.78l9.16-5.02v10.07a.46.46 0 0 1-.66.4zm10.64 4.26V17.27l9.16 5.02a.45.45 0 0 1-.03.79l-8.47 4.66a.45.45 0 0 1-.66-.4");
}

</style>
