<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuzlxcbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vuzlxcbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:axe" /></template>
