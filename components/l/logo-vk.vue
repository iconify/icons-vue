<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrh53-k1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hrh53-k1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-vk" /></template>
