<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd8hkcb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zd8hkcb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:icarus" /></template>
