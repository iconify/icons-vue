<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd78yzcxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd78yzcxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-cent-fill" /></template>
