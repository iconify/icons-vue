<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao9aj2b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ao9aj2b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bowling-bold" /></template>
