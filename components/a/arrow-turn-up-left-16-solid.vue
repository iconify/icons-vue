<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jacuf9bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jacuf9bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-up-left-16-solid" /></template>
