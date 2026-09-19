<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kajys0kmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kajys0kmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left-16-solid" /></template>
