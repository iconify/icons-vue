<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2bxbq90f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f2bxbq90f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:code-filled" /></template>
