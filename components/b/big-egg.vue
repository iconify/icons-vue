<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi80d9jib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gi80d9jib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:big-egg" /></template>
