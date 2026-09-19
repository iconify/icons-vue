<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__1v4b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b__1v4b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bucket-wheel-excavator" /></template>
