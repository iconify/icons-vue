<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi0206b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi0206b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-download-fill" /></template>
