<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szzww6bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szzww6bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:blocks" /></template>
