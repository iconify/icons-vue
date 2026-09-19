<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1_6q1b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z1_6q1b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:clock-filled" /></template>
