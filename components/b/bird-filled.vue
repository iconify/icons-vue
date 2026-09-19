<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdwq5tblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qdwq5tblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bird-filled" /></template>
