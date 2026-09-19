<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s08092quh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s08092quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hangul-filled" /></template>
