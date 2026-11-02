<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-d8ncw7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-d8ncw7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-down-up-line" /></template>
