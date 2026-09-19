<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4tnwe4rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4tnwe4rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:air-man" /></template>
