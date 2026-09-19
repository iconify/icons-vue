<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk1dk7bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qk1dk7bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jet-pack" /></template>
