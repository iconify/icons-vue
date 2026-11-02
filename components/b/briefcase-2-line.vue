<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wipf8mfog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wipf8mfog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:briefcase-2-line" /></template>
