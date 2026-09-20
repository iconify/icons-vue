<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq8u3fbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="vq8u3fbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:edit" /></template>
