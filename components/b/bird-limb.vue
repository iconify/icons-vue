<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zepxhpbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zepxhpbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bird-limb" /></template>
