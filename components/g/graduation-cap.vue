<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u893fxc0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u893fxc0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:graduation-cap" /></template>
