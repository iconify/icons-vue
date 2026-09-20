<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7g8utbwr.css';
import '../../css/v/v8v4y7b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7g8utbwr"/><path class="v8v4y7b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-2-line" /></template>
