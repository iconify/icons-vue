<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3u28ea3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3u28ea3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:byte" /></template>
