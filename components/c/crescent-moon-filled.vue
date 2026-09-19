<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4qznv4lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f4qznv4lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:crescent-moon-filled" /></template>
