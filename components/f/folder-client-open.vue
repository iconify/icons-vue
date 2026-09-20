<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0djsxb9c.css';
import '../../css/c/crdzj6byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="crdzj6byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-client-open" /></template>
