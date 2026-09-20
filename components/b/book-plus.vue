<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz_fsnb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz_fsnb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-plus" /></template>
