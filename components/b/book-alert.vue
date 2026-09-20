<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3u3mb96z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3u3mb96z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:book-alert" /></template>
