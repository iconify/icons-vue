<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4a0zvbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4a0zvbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:image-2-fill" /></template>
