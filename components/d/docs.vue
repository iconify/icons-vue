<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_fg-2buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q_fg-2buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:docs" /></template>
