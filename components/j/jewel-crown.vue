<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zznm4mbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zznm4mbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jewel-crown" /></template>
