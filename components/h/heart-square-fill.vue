<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2qss64im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2qss64im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:heart-square-fill" /></template>
