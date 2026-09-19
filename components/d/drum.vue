<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjq0_3_pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjq0_3_pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drum" /></template>
