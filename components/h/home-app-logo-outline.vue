<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m27_52kbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-app-logo-outline" /></template>
<style>
.m27_52kbs {
  fill: currentColor;
  d: path("M6.366 20q-.986 0-1.676-.69T4 17.635V12q0-.47.176-.9t.507-.763l5.634-5.635q.349-.354.79-.528T12 4q.45 0 .88.17q.431.171.783.532l5.635 5.635q.329.329.516.76T20 12v5.635q0 .985-.695 1.675q-.696.69-1.69.69zm0-1h11.25q.588 0 .986-.392q.398-.393.398-.974V12q0-.284-.104-.532t-.312-.437l-3.901-3.908l-1.995 1.989l3.562 3.542v3.596h-8.5v-3.596l6.22-6.238l-1.02-1.02q-.258-.257-.52-.327T11.992 5t-.449.079t-.531.337L5.396 11.03q-.188.188-.292.437T5 12v5.635q0 .58.393.972t.973.393m2.384-3.75h6.5v-2.175L12 9.825l-3.25 3.25z");
}

</style>
