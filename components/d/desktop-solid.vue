<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9kl6h36h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k9kl6h36h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:desktop-solid" /></template>
