<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzraisb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uzraisb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:alexa" /></template>
