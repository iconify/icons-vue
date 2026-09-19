<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1zs5b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iw1zs5b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:editorconfig" /></template>
