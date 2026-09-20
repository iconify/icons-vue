<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a22874bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a22874bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:folder-line" /></template>
