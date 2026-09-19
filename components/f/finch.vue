<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euya8fbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="euya8fbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:finch" /></template>
