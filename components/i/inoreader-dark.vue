<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di0i2020v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di0i2020v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inoreader-dark" /></template>
