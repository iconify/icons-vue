<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsep9da-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsep9da-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:document-remove" /></template>
