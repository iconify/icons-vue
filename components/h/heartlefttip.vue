<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs1v6ub8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vs1v6ub8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heartlefttip" /></template>
