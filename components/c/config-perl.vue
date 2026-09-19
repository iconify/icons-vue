<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_5izb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly_5izb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-perl" /></template>
