<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qarus5baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qarus5baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:fog" /></template>
