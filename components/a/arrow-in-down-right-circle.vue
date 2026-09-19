<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuq627b0r.css';
import '../../css/c/c5qcubb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuq627b0r"/><path class="c5qcubb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-right-circle" /></template>
