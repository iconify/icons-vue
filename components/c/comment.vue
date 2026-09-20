<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1ap0cjsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1ap0cjsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:comment" /></template>
