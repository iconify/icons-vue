<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8bdu7buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l8bdu7buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-nine-filled" /></template>
