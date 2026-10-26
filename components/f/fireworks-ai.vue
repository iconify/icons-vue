<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":127};
const content = `<path class="n8e211ywl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:fireworks-ai" /></template>
<style>
.n8e211ywl {
  fill: var(--svg-color--6720ff, #6720ff);
  d: path("m157.863 0l-29.877 71.595L98.081 0H78.897l32.777 78.266c2.719 6.53 9.095 10.748 16.2 10.748s13.467-4.218 16.2-10.72L177.048 0zm12.766 109.082l54.653-55.256l-7.455-17.587l-59.698 60.469c-4.989 5.059-6.418 12.514-3.657 19.044c2.746 6.474 9.095 10.664 16.171 10.664l.028.029l85.329-.21l-7.455-17.588l-77.902.435zM30.718 53.784l7.455-17.587L97.87 96.666c4.989 5.045 6.432 12.528 3.657 19.044c-2.746 6.489-9.122 10.664-16.171 10.664l-85.329-.196l-.028.028l7.455-17.587l77.902.435z");
}

</style>
