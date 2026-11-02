<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3kpvpa4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3kpvpa4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-down-fill" /></template>
