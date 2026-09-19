<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jivqpk97o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jivqpk97o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-broom" /></template>
