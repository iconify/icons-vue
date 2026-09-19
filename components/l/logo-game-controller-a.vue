<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvw6up7ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvw6up7ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-game-controller-a" /></template>
