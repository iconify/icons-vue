<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9k7gdnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tw9k7gdnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crosscut-saw" /></template>
