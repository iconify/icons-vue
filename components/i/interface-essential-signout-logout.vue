<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofc2p7fff.css';
import '../../css/o/o2idt1eal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ofc2p7fff"/><path class="o2idt1eal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-signout-logout" /></template>
