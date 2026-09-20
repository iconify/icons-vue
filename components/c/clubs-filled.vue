<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjgys6ave.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjgys6ave"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clubs-filled" /></template>
