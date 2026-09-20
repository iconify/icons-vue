<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz30t38ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz30t38ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:files-landscapes" /></template>
