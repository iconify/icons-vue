<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3th3mb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3th3mb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:hard-drive" /></template>
