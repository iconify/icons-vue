<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr7ozebwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr7ozebwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-2-fill" /></template>
