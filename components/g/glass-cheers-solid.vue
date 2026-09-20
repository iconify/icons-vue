<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-0n2e-vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k-0n2e-vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:glass-cheers-solid" /></template>
