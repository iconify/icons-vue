<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss96c8byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ss96c8byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:full-trash" /></template>
