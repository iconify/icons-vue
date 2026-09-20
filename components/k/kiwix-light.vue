<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgqiq1u1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgqiq1u1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kiwix-light" /></template>
