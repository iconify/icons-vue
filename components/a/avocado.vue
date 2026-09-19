<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjw7bkbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjw7bkbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:avocado" /></template>
