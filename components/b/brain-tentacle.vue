<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zziq5zbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zziq5zbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brain-tentacle" /></template>
