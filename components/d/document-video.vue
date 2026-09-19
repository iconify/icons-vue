<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed7ytxbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed7ytxbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-video" /></template>
