<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jxvubqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-missed-outgoing-outline" /></template>
<style>
.d1jxvubqk {
  fill: currentColor;
  d: path("m12 17.425l-9-9L4.4 7l7.6 7.6L17.6 9H13V7h8v8h-2v-4.575z");
}

</style>
