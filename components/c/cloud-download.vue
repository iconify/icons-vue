<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si8f9zaqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="si8f9zaqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-download" /></template>
