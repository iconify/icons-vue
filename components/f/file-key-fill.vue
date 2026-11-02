<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9kdqb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb9kdqb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-key-fill" /></template>
