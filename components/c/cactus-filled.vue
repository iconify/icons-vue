<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n93ug4cnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n93ug4cnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cactus-filled" /></template>
