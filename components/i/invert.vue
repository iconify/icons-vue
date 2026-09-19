<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5s_1sbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a5s_1sbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:invert" /></template>
