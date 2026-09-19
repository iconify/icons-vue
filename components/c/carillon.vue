<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksd0dwcta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksd0dwcta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:carillon" /></template>
