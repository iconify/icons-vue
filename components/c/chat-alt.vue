<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e__idhb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e__idhb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:chat-alt" /></template>
