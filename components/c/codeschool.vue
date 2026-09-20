<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jn2ac5gfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codeschool" /></template>
<style>
.jn2ac5gfe {
  d: path("M128 0C57.25 0 0 57.25 0 128s57.25 128 128 128s128-57.25 128-128S198.284 0 128 0zm0 232.727c-58.182 0-105.193-47.01-105.193-104.727C22.807 69.818 69.818 22.807 128 22.807c58.182 0 104.727 47.011 104.727 105.193c0 57.716-47.01 104.727-104.727 104.727zm-13.964-69.818L76.335 128l37.701-35.375V59.578L41.891 128l72.145 67.956V162.91zm27.462-103.33v33.046L179.2 128l-37.702 34.91v33.046L213.644 128l-72.146-68.422z");
  fill: var(--svg-color--53adc0, #53ADC0);
}

</style>
