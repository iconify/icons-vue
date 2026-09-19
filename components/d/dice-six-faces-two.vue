<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r94wsub5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r94wsub5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-six-faces-two" /></template>
