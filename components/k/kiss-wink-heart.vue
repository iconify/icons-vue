<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0reff-sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":512};
const content = `<path class="v0reff-sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:kiss-wink-heart" /></template>
