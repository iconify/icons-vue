<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_1rp79vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e_1rp79vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:eclipse-wordmark" /></template>
