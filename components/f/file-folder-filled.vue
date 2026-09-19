<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rogd2jebs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rogd2jebs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-folder-filled" /></template>
