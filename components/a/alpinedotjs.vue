<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2s84ct4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2s84ct4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alpinedotjs" /></template>
