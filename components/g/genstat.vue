<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/punybqr-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="punybqr-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:genstat" /></template>
