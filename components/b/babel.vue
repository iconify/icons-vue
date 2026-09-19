<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbwwa7bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":422,"height":512};
const content = `<path class="sbwwa7bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:babel" /></template>
