<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3q2jqs8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3q2jqs8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:automatic-sas" /></template>
