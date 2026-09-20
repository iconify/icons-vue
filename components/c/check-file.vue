<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2wpoel1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="r2wpoel1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:check-file" /></template>
