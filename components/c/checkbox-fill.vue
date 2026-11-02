<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7zffl6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb7zffl6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:checkbox-fill" /></template>
