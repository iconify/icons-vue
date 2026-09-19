<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brmlh4b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="brmlh4b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-ttf-filled" /></template>
