<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbnrnkj8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nbnrnkj8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-party-horn-and-party-hat" /></template>
