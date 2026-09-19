<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ngxvwpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1ngxvwpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hive-mind" /></template>
