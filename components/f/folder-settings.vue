<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2sa77byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-settings" /></template>
<style>
.z2sa77byc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm5.649 6.283q.061-1.233 1.296-1.231h.111q1.234-.002 1.295 1.232q.006.111.102.167l.033.019q.093.053.192.002q1.097-.562 1.714.506l.056.097q.617 1.069-.421 1.737q-.092.06-.092.172v.034q0 .112.094.172q1.036.668.418 1.737l-.055.097q-.617 1.068-1.714.505q-.099-.05-.196.005l-.025.015q-.1.058-.106.17q-.061 1.233-1.296 1.231h-.111q-1.234.002-1.295-1.232q-.006-.111-.102-.167l-.033-.019q-.093-.053-.192-.002q-1.097.562-1.714-.506l-.056-.097q-.617-1.069.421-1.737q.092-.06.092-.172v-.034q0-.112-.094-.172q-1.036-.668-.418-1.737l.055-.097q.617-1.068 1.714-.505q.099.05.196-.005l.025-.015q.1-.058.106-.169");
}

</style>
