<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":301};
const content = `<path class="z7kz7tbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:daily-icon" /></template>
<style>
.z7kz7tbxp {
  d: path("M0 300.931V217.94L108.451 0H256v83.029L147.603 300.931z");
}

</style>
