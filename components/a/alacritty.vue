<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au9or3-rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":449,"height":512};
const content = `<path class="au9or3-rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:alacritty" /></template>
