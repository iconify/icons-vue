<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iirs8ac6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iirs8ac6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:honey" /></template>
