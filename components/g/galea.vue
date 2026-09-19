<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shqi23r1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shqi23r1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:galea" /></template>
