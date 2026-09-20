<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3wdxibrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="p3wdxibrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chat-typing-solid" /></template>
