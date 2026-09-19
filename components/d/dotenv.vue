<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-je2tbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-je2tbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dotenv" /></template>
