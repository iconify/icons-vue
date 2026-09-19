<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aki4zgn5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aki4zgn5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beast-eye" /></template>
