<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7m4u5b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7m4u5b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-ace" /></template>
