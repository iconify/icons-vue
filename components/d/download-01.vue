<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anpr5tboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anpr5tboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:download-01" /></template>
