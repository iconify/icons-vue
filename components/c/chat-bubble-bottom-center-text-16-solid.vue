<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7c6r5bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y7c6r5bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center-text-16-solid" /></template>
