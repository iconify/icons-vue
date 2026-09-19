<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg-0k0bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jg-0k0bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-dots-fill" /></template>
