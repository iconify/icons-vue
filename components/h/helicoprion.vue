<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glhvnvnoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glhvnvnoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:helicoprion" /></template>
