<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afg9v3b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="afg9v3b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-cursor" /></template>
