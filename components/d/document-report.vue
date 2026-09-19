<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbk9oiw8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbk9oiw8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document-report" /></template>
