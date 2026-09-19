<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2_os0b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n2_os0b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dinosaur-rex" /></template>
