<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw8unpi4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:infra" /></template>
<style>
.cw8unpi4z {
  fill: var(--svg-color--fdb913, #fdb913);
  fill-rule: evenodd;
  d: path("m12 3l7.412 6.353v5.294L12 21l-7.412-6.078v-5.57zm-6.882 7.03v4.204l2.562-2.102zm2.986 2.447L5.27 14.795l6.464 5.294v-4.632zm4.16 2.98v4.622l6.46-5.538l-2.732-2.139zm4.151-3.404l2.467 1.932v-3.954zm2.32-2.584l-2.754 2.25l-3.716-2.911V3.926zm-7-5.543v4.887l-3.631 2.98l-2.838-2.329l6.47-5.532zM12 9.28l-3.478 2.859L12 14.98l3.563-2.922l-3.558-2.784z");
}

</style>
