<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va-qs_okh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="va-qs_okh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:alarm-clock" /></template>
