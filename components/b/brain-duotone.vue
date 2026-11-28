<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t186o8euu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary t186o8euu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:brain-duotone" /></template>
