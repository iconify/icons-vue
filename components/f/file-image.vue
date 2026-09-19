<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd6c9-4-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd6c9-4-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:file-image" /></template>
