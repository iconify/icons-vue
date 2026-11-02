<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elp4ijr-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elp4ijr-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-6-fill" /></template>
