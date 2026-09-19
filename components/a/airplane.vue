<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce2nadbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ce2nadbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:airplane" /></template>
