<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjoq5hbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjoq5hbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:capybara" /></template>
