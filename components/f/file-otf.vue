<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppev5fk1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ppev5fk1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-otf" /></template>
