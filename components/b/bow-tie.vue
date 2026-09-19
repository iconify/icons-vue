<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5hvg5b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g5hvg5b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bow-tie" /></template>
