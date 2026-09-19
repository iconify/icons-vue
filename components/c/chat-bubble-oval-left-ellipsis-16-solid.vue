<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf5p35bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vf5p35bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left-ellipsis-16-solid" /></template>
