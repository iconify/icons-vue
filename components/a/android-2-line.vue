<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yszkt334k.css';
import '../../css/t/tj0901bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yszkt334k"/><path class="tj0901bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:android-2-line" /></template>
