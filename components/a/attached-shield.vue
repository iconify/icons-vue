<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me234t_fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="me234t_fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:attached-shield" /></template>
