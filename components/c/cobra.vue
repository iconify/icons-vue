<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twcjeh8ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="twcjeh8ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cobra" /></template>
