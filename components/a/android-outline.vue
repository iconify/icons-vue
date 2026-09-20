<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r---78b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r---78b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:android-outline" /></template>
