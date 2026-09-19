<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe78kyb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pe78kyb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:hide-2" /></template>
