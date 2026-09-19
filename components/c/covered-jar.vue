<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o66gqk1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o66gqk1ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:covered-jar" /></template>
