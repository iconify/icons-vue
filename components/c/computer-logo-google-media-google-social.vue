<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obwdk16ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="obwdk16ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-logo-google-media-google-social" /></template>
