<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb8-7u1lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb8-7u1lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:belgium" /></template>
