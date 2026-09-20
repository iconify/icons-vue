<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj3q2bi4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj3q2bi4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kaios" /></template>
