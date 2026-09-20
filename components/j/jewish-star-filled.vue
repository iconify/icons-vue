<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukxbgsb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukxbgsb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:jewish-star-filled" /></template>
