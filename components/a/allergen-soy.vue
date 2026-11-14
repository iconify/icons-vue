<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpwutp5ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:allergen-soy" /></template>
<style>
.rpwutp5ni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.784 11.776Q3.824 5.25 11 5.25q6.44 0 8.743 5.256q.713-1.112 1.022-2.653q.014-.073.042-.141t.07-.129q.041-.062.093-.114q.053-.052.114-.093t.13-.069t.14-.043q.073-.014.147-.014t.146.015t.141.042t.129.07q.062.041.114.093q.052.053.093.114t.069.13q.028.068.043.14t.014.147q0 .074-.015.146q-.522 2.615-2.074 4.25Q18.081 18.75 11 18.75q-7.176 0-9.216-6.526q-.07-.224 0-.448M4.25 12q0 2.75 2.75 2.75q1.314 0 2-.628q.686.628 2 .628t2-.628q.686.628 2 .628q2.75 0 2.75-2.75T15 9.25q-1.314 0-2 .628q-.686-.628-2-.628t-2 .628q-.686-.628-2-.628q-2.75 0-2.75 2.75");
}

</style>
