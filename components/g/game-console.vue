<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qor6go1jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qor6go1jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:game-console" /></template>
