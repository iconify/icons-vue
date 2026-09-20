<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0djsxb9c.css';
import '../../css/m/m95mj6b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="m95mj6b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-queue-open" /></template>
