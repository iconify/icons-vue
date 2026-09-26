<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1vx54dmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fast-forward-fill" /></template>
<style>
.q1vx54dmg {
  fill: currentColor;
  d: path("M1 7.504964C1 5.313398 3.619285 4.182505 5.214383 5.685378L10.371506 10.544331C11.209498 11.333873 11.209498 12.666127 10.371506 13.455669L5.214383 18.314623C3.619286 19.817496 1 18.686603 1 16.495037ZM13 7.504963C13 5.313397 15.619285 4.182504 17.214383 5.685377L22.371507 10.544331C23.209499 11.333873 23.209499 12.666127 22.371507 13.455669L17.214383 18.314623C15.619285 19.817496 13 18.686603 13 16.495037Z");
}

</style>
