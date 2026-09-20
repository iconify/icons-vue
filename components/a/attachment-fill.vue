<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw7jxtb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw7jxtb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-fill" /></template>
