<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia79h9v2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia79h9v2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:eye-target" /></template>
