<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c96ozvl4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c96ozvl4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-seven-filled" /></template>
