<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hruesdb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hruesdb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:aligncenter" /></template>
