<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7diirbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t7diirbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-black-suit" /></template>
