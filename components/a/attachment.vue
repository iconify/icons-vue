<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll0cyjbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="ll0cyjbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:attachment" /></template>
