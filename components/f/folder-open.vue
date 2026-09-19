<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgg-w0bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgg-w0bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:folder-open" /></template>
