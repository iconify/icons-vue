<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia46pmwzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia46pmwzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:beach-access" /></template>
