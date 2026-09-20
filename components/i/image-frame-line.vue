<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g85wt0b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g85wt0b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:image-frame-line" /></template>
