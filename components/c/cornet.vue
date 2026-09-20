<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teymdtb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="teymdtb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:cornet" /></template>
