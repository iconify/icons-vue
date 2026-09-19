<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3vmb7bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u3vmb7bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-smile-fill" /></template>
