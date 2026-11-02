<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lab7x-wem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lab7x-wem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ham-fill" /></template>
