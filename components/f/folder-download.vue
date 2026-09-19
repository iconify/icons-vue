<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta4y7xbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta4y7xbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:folder-download" /></template>
