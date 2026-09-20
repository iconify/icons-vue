<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6u44ac-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="d6u44ac-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:colordropper" /></template>
