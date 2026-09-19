<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lesw936ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lesw936ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cursing-face" /></template>
