<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp0zracut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xp0zracut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:carets-expand-vertical" /></template>
