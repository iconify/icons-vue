<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiazq6bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiazq6bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-line" /></template>
