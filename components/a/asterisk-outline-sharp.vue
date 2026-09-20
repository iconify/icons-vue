<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-_nublke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:asterisk-outline-sharp" /></template>
<style>
.t-_nublke {
  fill: currentColor;
  d: path("M11.5 20v-6.792l-4.804 4.81l-.713-.714l4.81-4.804H4v-1h6.792l-4.81-4.804l.714-.694l4.804 4.81V4h1v6.812l4.804-4.81l.694.694l-4.81 4.804H20v1h-6.812l4.81 4.804l-.694.713l-4.804-4.81V20z");
}

</style>
