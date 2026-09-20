<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h-e9fho4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:alien-monster" /></template>
<style>
.h-e9fho4o {
  fill: var(--svg-color--553986, #553986);
  d: path("M26 31h4v4h-4zM6 31h4v4H6zm24-21h-2V8h-2V6h-3V2h-2v4h-6V2h-2v4h-3v2H8v2H6v7H2v2h4v7h4v5h5v-5h6v5h5v-5h4v-7h4v-2h-4zM16 21h-4v-8h4zm4 0v-8h4v8zM34 6h2v11h-2zM0 6h2v11H0z");
}

</style>
