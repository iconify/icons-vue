<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bjticir2m"/><path class="e4r75xb8h"/><path class="psu9b1cco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-buck-opened" /></template>
<style>
.bjticir2m {
  fill: var(--svg-color--c0c8d8, #c0c8d8);
  d: path("M29.5 5.5H18.2l-2.1 4.2H4.3v16.8h25.2zm-2.1 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1zm-1.7 4H.5l3.8 12.8h25.2z");
}

.e4r75xb8h {
  fill: var(--svg-color--4a69a5, #4a69a5);
  d: path("M15.95 12.72h-1.52v4.31l1.85 1.86h-2.23l-2.43-2.44v-3.73H10v4.42l3.31 3.31h4.46l1.6 1.6h-4.28l3.61 3.71L13.42 31h2.08l5.28-5.32l-2.01-2h10.67v.67l-4.61 2.75l-3.87 3.9h2.2l2.64-2.68L31 25.2v-3.15h-4.91l-1.67-1.68l1.9-1.89v-4.24h-1.58v3.53l-1.55 1.53l-1.37-1.44v-3.62h-1.49v4.31l3.48 3.5h-2.12l-5.74-5.69z");
}

.psu9b1cco {
  fill: var(--svg-color--4a69a5, #4a69a5);
  d: path("M24.01 24.65h-2.08l1 1.07z");
}

</style>
