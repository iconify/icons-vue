<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw4irqots.css';
import '../../css/l/lzg5bgbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vw4irqots"/><path class="lzg5bgbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbwhois" /></template>
