<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5gqb4bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5gqb4bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-search" /></template>
