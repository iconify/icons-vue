<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7f-7pw_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7f-7pw_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cog-outline" /></template>
