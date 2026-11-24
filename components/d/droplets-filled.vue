<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj0sl0bxe.css';
import '../../css/o/oevx49bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj0sl0bxe"/><path class="oevx49bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:droplets-filled" /></template>
