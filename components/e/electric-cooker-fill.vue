<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm4n3ybtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm4n3ybtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:electric-cooker-fill" /></template>
