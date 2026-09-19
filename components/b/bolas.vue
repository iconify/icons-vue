<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx7jiwxxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gx7jiwxxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bolas" /></template>
