<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhqcrqjow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhqcrqjow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:golem-head" /></template>
