<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fko3yrtpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fko3yrtpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bed-lamp" /></template>
