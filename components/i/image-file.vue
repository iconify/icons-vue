<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk9dx8b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="pk9dx8b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:image-file" /></template>
