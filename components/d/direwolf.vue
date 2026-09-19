<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve0ln5b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ve0ln5b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:direwolf" /></template>
