<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygqz0ob6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygqz0ob6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:behance" /></template>
