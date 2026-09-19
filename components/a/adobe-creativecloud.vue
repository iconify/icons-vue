<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7aosk7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sx7aosk7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-creativecloud" /></template>
