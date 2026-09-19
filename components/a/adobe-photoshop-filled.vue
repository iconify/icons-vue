<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilx1rbbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ilx1rbbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adobe-photoshop-filled" /></template>
