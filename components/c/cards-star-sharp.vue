<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nugmjccfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cards-star-sharp" /></template>
<style>
.nugmjccfm {
  fill: currentColor;
  d: path("m12.34 12.192l1.93-1.163l1.928 1.163l-.523-2.196l1.712-1.475l-2.24-.186l-.878-2.066l-.877 2.066l-2.24.186l1.712 1.475zM4.586 21.03L2.927 8.066l2.612-.254v10.65h12.8l.086.825zm2.954-4.567V3H21v13.462z");
}

</style>
