<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rake5402i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rake5402i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-rightbar-open-fill" /></template>
