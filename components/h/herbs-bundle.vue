<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4-ahbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo4-ahbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:herbs-bundle" /></template>
