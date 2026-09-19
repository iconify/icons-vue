<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbjah4bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbjah4bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cannon-ball" /></template>
