<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7kngvb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w7kngvb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:healing-shield" /></template>
