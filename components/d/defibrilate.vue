<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arz71r5ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="arz71r5ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:defibrilate" /></template>
