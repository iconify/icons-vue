<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb4ghvnyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb4ghvnyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:gitlab" /></template>
