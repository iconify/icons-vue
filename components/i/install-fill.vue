<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn0ovxbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn0ovxbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:install-fill" /></template>
