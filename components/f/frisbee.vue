<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6q8jg6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aa6q8jg6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frisbee" /></template>
