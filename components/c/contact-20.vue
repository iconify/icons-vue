<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx89adb5k.css';
import '../../css/p/p-13vkqjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bx89adb5k"/><path class="p-13vkqjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contact-20" /></template>
