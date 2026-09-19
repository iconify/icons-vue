<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln14l76-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ln14l76-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clownfish" /></template>
