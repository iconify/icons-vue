<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzlqmi-kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vzlqmi-kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:love-mystery" /></template>
