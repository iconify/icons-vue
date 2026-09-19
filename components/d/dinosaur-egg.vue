<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1xml0bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1xml0bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dinosaur-egg" /></template>
