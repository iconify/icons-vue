<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etdo7y9jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etdo7y9jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-queen-clubs" /></template>
