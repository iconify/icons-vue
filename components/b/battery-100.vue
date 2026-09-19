<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8k9ylbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8k9ylbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battery-100" /></template>
