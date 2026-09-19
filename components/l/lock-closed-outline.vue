<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pth7mvs2w.css';
import '../../css/f/ff9jhsbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pth7mvs2w"/><rect class="ff9jhsbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:lock-closed-outline" /></template>
