<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn1qobchn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sn1qobchn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chewed-heart" /></template>
