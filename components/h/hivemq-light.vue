<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hke8i3ela.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hke8i3ela"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hivemq-light" /></template>
