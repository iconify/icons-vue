<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dszkiqsya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dszkiqsya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:f-clef" /></template>
