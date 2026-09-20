<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bof0itb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bof0itb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:expo-light" /></template>
