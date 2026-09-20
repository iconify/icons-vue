<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm69rlbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="nm69rlbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:create-new" /></template>
