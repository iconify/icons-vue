<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bma74xb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":405,"height":512};
const content = `<path class="bma74xb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lime" /></template>
