<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx9qymyxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fx9qymyxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:console" /></template>
