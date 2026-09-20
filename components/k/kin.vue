<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snc3baboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kin" /></template>
<style>
.snc3baboy {
  fill: var(--svg-color--7e43ff, #7e43ff);
  d: path("m12 3l7.941 4.5v9l-7.94 4.5l-7.942-4.5v-9z");
}

</style>
