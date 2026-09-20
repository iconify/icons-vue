<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz1nfzvvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gz1nfzvvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:conversation" /></template>
