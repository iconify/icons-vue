<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hig8vmu5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hig8vmu5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:audio-document-outline" /></template>
