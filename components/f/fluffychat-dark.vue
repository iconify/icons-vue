<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx040bc6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bx040bc6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluffychat-dark" /></template>
