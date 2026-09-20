<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m68_46y6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m68_46y6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-download" /></template>
