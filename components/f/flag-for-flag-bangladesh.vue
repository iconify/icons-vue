<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="v4b77y8vr"/><circle class="hzzz1jv6x"/><circle class="htnvsqbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-bangladesh" /></template>
<style>
.htnvsqbki {
  cx: 26px;
  cy: 32px;
  r: 14.1px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.hzzz1jv6x {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--699635, #699635);
}

.v4b77y8vr {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--75a843, #75a843);
}

</style>
