<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/barxp169s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="barxp169s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:japan" /></template>
