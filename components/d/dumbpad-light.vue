<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsxbr0b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsxbr0b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbpad-light" /></template>
